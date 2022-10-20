# DBSGen
This is a Tensorflow implementation of the DBSGen method.

Background subtraction is a significant task in computer vision and an essential step for many real world applications. One of the challenges for background subtraction methods is dynamic background, which constitutes stochastic movements in some parts of the background. In this paper, we have proposed a new background subtraction method, called DBSGen, which uses two generative neural networks, one for dynamic motion removal and another for background generation. At the end, the foreground moving objects are obtained by a pixel-wise distance threshold based on a dynamic entropy map. DBSGen is an end-to-end, unsupervised optimization method with a near real-time frame rate. The performance of the method is evaluated over dynamic background sequences and it outperforms most of state-of-the-art unsupervised methods.
![alt text](https://github.com/FatemeBahri/DBSGen/blob/main/images/Block_diagram.png?raw=true)
