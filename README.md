- python 版本：3.6.0
- skimage 版本：0.14.2

子模块名称   |  主要实现功能
-------------|-------------
color        | 色彩空间变换
data         | 示例数据
draw         | 操作于numpy数组上的基本图形绘制，包括线条、矩形、圆和文本等
exposure     | 图片强度调整，如亮度调整、直方图均衡等
external     | 
feature      | 特征检测与提取等
filters      | 图像增强、边缘检测、排序滤波器、自动阈值等
future       | 
graph        | 
io           | 图像（视频）读取、显示与保存
measure      | 图像属性的测量，如相似性或等高线等
morphology   | 形态学操作，如开闭运算、骨架提取等
novice       | 
restoration  | 图像恢复
segmentation | 图像分割
transform    | 几何变换或其它变换，如旋转、拉伸和拉东变换等
util         | 通用函数
viewer       | 示例数据


### skimage 大纲

#### 1. [图像读写与查看【模块:data,io】](https://github.com/devshilei/skimage_code/tree/master#%E5%9B%BE%E5%83%8F%E8%AF%BB%E5%86%99%E4%B8%8E%E6%9F%A5%E7%9C%8B)

#### 2. [像素操作【模块:draw】](https://note.youdao.com/)

#### 3. [图像变换【模块:transform】](https://note.youdao.com/)

#### 4. [图像直方图【模块:exposure】](https://note.youdao.com/)

#### 5. [图像增强【模块:filters】](https://note.youdao.com/)

#### 6. [图像滤波【模块:filters】](https://note.youdao.com/)

#### 7. [图像形态学【模块:morphology】](https://note.youdao.com/)

#### 8. [图像分割【模块:segmentation】](https://note.youdao.com/)

#### 9. [图像恢复【模块:restoration】](https://note.youdao.com/)


### 图像读写与查看


```
from skimage import io
# 查看本地图片并显示
img=io.imread('d:/dog.jpg')
io.imshow(img)
io.show()
```


