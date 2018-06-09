# GermanTrafficSignDetection
## Intro
This project builds a Deep learning model that localizes (with a bounding box) and identifies German traffic signs.

The algorithm is an adaptation of [Fastai's](https://www.fast.ai) [Lesson 9](https://github.com/fastai/fastai/blob/master/courses/dl2/pascal-multi.ipynb) to the problem of Traffic Sign Detection (i.e. bounding box regression + identification) on the  [German Traffic Sign Detection dataset](http://benchmark.ini.rub.de/?section=gtsdb&subsection=news) 

## Results Summary
Below are results on 16 validation set images
![ResSummary](ValidSetResults/ResultsSummary.png)

For a better view of each results, go to the end of this Readme.

## Conclusion
Although the results are far from satisfactory, we were able to reach encouraging results with only ~500 training examples. 
Here are a list of things we could do to improve these results:
* Add more data
* Use a multi-pyramidal architecture, such as [RetinaNet](https://arxiv.org/pdf/1708.02002.pdf)
* Conserve higher-res images for training (in order to avoid memory issues with my GPU, I had to downscale images to 448x448)

## Appendix 1: zoom-in on each result
![results_0](ValidSetResults/results_0.png)
![results_1](ValidSetResults/results_1.png)
![results_2](ValidSetResults/results_2.png)
![results_3](ValidSetResults/results_3.png)
![results_4](ValidSetResults/results_4.png)
![results_5](ValidSetResults/results_5.png)
![results_6](ValidSetResults/results_6.png)
![results_7](ValidSetResults/results_7.png)
![results_8](ValidSetResults/results_8.png)
![results_9](ValidSetResults/results_9.png)
![results_10](ValidSetResults/results_10.png)
![results_11](ValidSetResults/results_11.png)
![results_12](ValidSetResults/results_12.png)
![results_13](ValidSetResults/results_13.png)
![results_14](ValidSetResults/results_14.png)
![results_15](ValidSetResults/results_15.png)

