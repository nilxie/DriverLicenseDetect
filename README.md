# DriverLicenseIdentify
***
这是一个驾驶证识别的系统，其目标是成为一个高效且准确的驾驶证识别系统。目前正处于开发阶段(第一个基于OpenCV的项目)

更新日志

<<<<<<< HEAD
###7.24
1. 将方法封装成类。
2. 参考[EasyPR](https://github.com/liuruoze/EasyPR)项目，plate_locate的方法。改写，使其符合驾驶证特征。
3. 对驾驶证中的图像进行定位，通过判断其最小矩阵的特征，矩阵的角度来判断其是否满足要求。
4. 正常图像可定位所有信息所在的位置，但对反光或是图像清晰度低，色差较小的情况，难以准确定位所有的信息位置。

###7.25
1. 发现通过连通区的方法定位信息不够准确，不能准确定位关键信息，增大模式识别的工作量。
2. 尝试通过颜色定位的方法，先初步定位红色水印位置，删除图片中多余的部分。
3. 尝试Hough算法，还在理解中
=======
7.24
1. 将方法封装成类
2. 参考[EasyPR](https://github.com/liuruoze/EasyPR)项目，plate_locate的方法。改写，使其符合驾驶证特征。
3. 对驾驶证中的图像进行定位，通过判断其最小矩阵的特征，矩阵的角度来判断其是否满足要求
4. 正常图像可定位所有信息所在的位置，但对反光或是图像清晰度低，色差较小的情况，难以准确定位所有的信息位置
>>>>>>> 617c3eb6908e94d5bc3dc1ade8375c2d3cb94e43
