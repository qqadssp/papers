# papers
2018-06-08  
《DetNet: A Backbone network for Object Detection》  
arXiv 2018  
Abstract: 最近基于CNN的目标检测器，不管单阶段方法如YOLO、SSD和RetinaNet，或者两阶段方法如Faster R-CNN、R-FCN和FPN，通常尝试直接在为图像分类产生的ImageNet预训练模型上进行调整。而很少对专为目标识别定制的主干特征提取器进行讨论。更重要的一点，图像分类任务和目标检测任务有几点不同。(i) 最近的目标检测器，如FPN和RetinaNet，通常引入对于目标分类任务来讲额外的阶段来处理不同尺寸的目标。(ii) 目标检测不仅需要识别目标实例的类别，还需要空间定位位置。大量降采样因子带来大的可感受域，这对图像分类有利，但削减了目标检测的能力。由于图像分类和目标识别的差别，本文提出DetNet，一个全新的为目标检测定制的主干网络。此外，DetNet相对于用于图像分类的传统主干网络来讲包含额外阶段，同时在深层保留高空间分辨率。无需任何修饰，基于DetNet的方法获得了MSCOCO标准测试中目标检测和实例分割最新水平结果。  
link: https://arxiv.org/abs/1804.06215  

