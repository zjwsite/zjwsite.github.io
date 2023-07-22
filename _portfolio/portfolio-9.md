---
title: "Embedded Human Pose Estimation"
excerpt: ""
collection: portfolio
---
![](/images/embedded_hpe.jpg)

It is the most difficult course project I ever had. And it is still on processing. The project aims to deploy deep learning models for human pose estimation in the very-low-cost microprocesser!

The demo only predicts the upper body of the object. Because of the ckpt is provided by teaching assistant. We train and quantize our own model, but it runs bad in the chip. I still don't know why. To achieve the whole pipeline, several 3rd-party dependencies are needed. Such as TinyEngine, TinyNeuralNetwork, OpenMV, TF-Lite. So the entire project is not easy. I first thought the project is maybe about running models on jetson nano, tx2. Turns out that I underestimate the difficulty. The final reports can be find in [here](https://github.com/zjwsite/zjwsite.github.io/blob/master/embedded_hpe.pdf).

"This is not over."
