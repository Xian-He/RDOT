# RDOT
三维模板跟踪渲染数据集(a Render Dataset for Object Tracking)

## 摘要
本数据集为大型的高真实感、基准位姿无误差的RGB图像数据集, 对场景 的真实性和模型复杂程度、运动模式、光照变化、 噪声、运动模糊和遮挡等情况进行了定量合理的控制. RDOT数据集由6个场景、12个物体、12种运动模式组合得到864个基础数据集, 在基础数据集中选择了四分之一的序列进行4种不同的场景设置, 包括2种光照变化、2种不同程度的噪声、2种不同程度的运动模糊以及1种遮挡, 组成了较为复杂的7组共1512个增强数据集. RDOT数据集每个序列300帧, 共生成712800帧, 是目前最大的三维跟踪数据集。

## 渲染效果图
* 三维模型
<img src="https://github.com/Xian-He/RDOT/raw/master/e.g/models.png">

* 运动曲线

<img src="https://github.com/Xian-He/RDOT/raw/master/e.g/curves.png">

* 场景效果图

![img](https://github.com/Xian-He/RDOT/raw/master/e.g/scenes.png)

* 不同的场景设置效果图

![img](https://github.com/Xian-He/RDOT/raw/master/e.g/differentScenesSettings.png)

## 与其他数据集对比

![img](https://github.com/Xian-He/RDOT/raw/master/e.g/otherBenchmark.png)

## 评测结果
我们利用两种不同的评估方法对目前主流的6中算法进行测评，测评结果如下图。

![img](https://github.com/Xian-He/RDOT/raw/master/e.g/A_AED.png)

![img](https://github.com/Xian-He/RDOT/raw/master/e.g/A_AD.png)

![img](https://github.com/Xian-He/RDOT/raw/master/e.g/C_AED.png)

![img](https://github.com/Xian-He/RDOT/raw/master/e.g/C_AD.png)

## 完整数据集下载
链接：https://pan.baidu.com/s/1B8h4_Wlqt38ng7oYSvxtEQ 
提取码：d8ax

## 联系
如果你有任何问题，请联系：hexian_18@qq.com.
