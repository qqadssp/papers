## 2018-06-08  

---
**《DetNet: A Backbone network for Object Detection》**  
  
**arXiv 2018**  
  
**Abstract:** 最近基于CNN的目标检测器，不管单阶段方法如YOLO、SSD和RetinaNet，或者两阶段方法如Faster R-CNN、R-FCN和FPN，通常尝试直接在为图像分类产生的ImageNet预训练模型上进行调整。而很少对专为目标识别定制的主干特征提取器进行讨论。更重要的一点，图像分类任务和目标检测任务有几点不同。(i) 最近的目标检测器，如FPN和RetinaNet，通常引入对于目标分类任务来讲额外的阶段来处理不同尺寸的目标。(ii) 目标检测不仅需要识别目标实例的类别，还需要空间定位位置。大量降采样因子带来大的可感受域，这对图像分类有利，但削减了目标检测的能力。由于图像分类和目标识别的差别，本文提出DetNet，一个全新的为目标检测定制的主干网络。此外，DetNet相对于用于图像分类的传统主干网络来讲包含额外阶段，同时在深层保留高空间分辨率。无需任何修饰，基于DetNet的方法获得了MSCOCO标准测试中目标检测和实例分割最新水平结果。  
  
**Link:** https://arxiv.org/abs/1804.06215  

---
**《Multi-scale Location-aware Kernel Representation for Object Detection》**  

**CVPR 2018**  

**Abstract:** 尽管Faster R-CNN和它的变体在目标检测领域显示出理想的性能，他们只挖掘目标提议的简单一阶表征，用于最后的分类和回归。近期分类方法证明，将高阶表征统计整合入深度卷积神经网络可以获得可观的改进，但他们的目的是通过丢弃位置信息对整个图像建模，所以不能直接用于目标检测。本文中，我们尝试在目标检测中发掘高阶统计，意在对目标提议产生更有识别力的表征，增强检测器性能。为了这个目的，我们提出全新的Multi-scale Location-aware Kernel Representation (MLKP)来捕捉目标提议中深度特征的高阶统计。MLKP可以高效的在修正的多尺度特征图上进行计算，使用低维多项式核近似。更进一步，不同于已存在的少阶数全局表征，MLKP对位置有记忆性且位置敏感，因此很容易用于目标检测。通过整合如Faster R-CNN框架，MLKP获得与最新水平相比非常有竞争力的表现，在PASCAL VOC2007上改进4.9% mAP，在VOC2012上改进4.7% mAP，在MSCOCO上改进5.0%(在IOU=[0.5:0.05:0.95]的AP)。代码地址：http://github.com/Hwang64/MLKR。  

**Link:** https://arxiv.org/abs/1804.00428

