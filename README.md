# DBSGen
This is a Tensorflow implementation of the DBSGen method.

Background subtraction is a significant task in computer vision and an essential step for many real world applications. One of the challenges for background subtraction methods is dynamic background, which constitutes stochastic movements in some parts of the background. In this paper, we have proposed a new background subtraction method, called DBSGen, which uses two generative neural networks, one for dynamic motion removal and another for background generation. At the end, the foreground moving objects are obtained by a pixel-wise distance threshold based on a dynamic entropy map. DBSGen is an end-to-end, unsupervised optimization method with a near real-time frame rate. The performance of the method is evaluated over dynamic background sequences and it outperforms most of state-of-the-art unsupervised methods.

A block diagram of DBSGen is presented in the following figure. Input images and fixed images are shown in blue. The end-to-end modules are depicted in green. Foreground segmentation modules and final binary segmented results are represented in pink and yellow, respectively.

![alt text](https://github.com/FatemeBahri/DBSGen/blob/main/images/Block_diagram.png?raw=true)

Qualitative results of DBSGen can be observed in the below figure. Each row shows the intermediate and final results for one frame of each video. Columns show input frames, difference of the input frames and the fixed image, the obtained foreground images, the binary segmented results, the post-processed segmented results and ground-truths, successively.

![alt text](https://github.com/FatemeBahri/DBSGen/blob/main/images/qualitative.jpg?raw=true)
