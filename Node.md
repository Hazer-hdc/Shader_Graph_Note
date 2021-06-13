# Artistic美术
## Channel Mixer颜色通道混合
颜色通道混合
![](image/2021-06-12-21-18-58.png)

## Contrast对比度
![](image/2021-06-12-21-19-51.png)

## Hue色调

## Invert colors反转颜色

## Replacce Color替换颜色
用一个颜色替换另一个颜色，可以调整过渡
![](image/2021-06-12-21-22-24.png)

## Saturation饱和度

## White balance白平衡
如果想要暖色调
![](image/2021-06-12-21-23-34.png)

## Blend混合
可以混合两张textrue
![](image/2021-06-12-21-24-53.png)

## Dither抖动
![](image/2021-06-12-21-25-41.png)

## Channel Mask
![](image/2021-06-12-21-26-10.png)

## Color mask
如果想要屏蔽图像中所有的绿色像素
![](image/2021-06-12-21-27-20.png)

## Normal blend法线混合
两张法线贴图的混合
![](image/2021-06-12-21-28-11.png)
![](image/2021-06-12-21-28-16.png)

## Normal From Height
从高度图生成法线贴图
![](image/2021-06-12-21-29-10.png)

## Normal From Texture
从texture生成法线贴图
![](image/2021-06-12-21-29-42.png)

## Normal strength法线强度
改变法线强度
![](image/2021-06-12-21-30-47.png)
![](image/2021-06-12-21-30-58.png)

## Colorspace Conversion
颜色空间转换，如果想要把颜色分开，这是非常有用的
![](image/2021-06-12-21-34-38.png)
![](image/2021-06-12-21-34-43.png)

# Channel通道
## split
![](image/2021-06-12-21-36-01.png)
![](image/2021-06-12-21-36-22.png)

## Combine
将不同通道组合在一起
![](image/2021-06-12-21-36-51.png)

## Flip翻转
可以翻转一些颜色
![](image/2021-06-12-21-37-41.png)

## Swizzle
可以改变向量的各个分量的顺序。
如果使用这个节点，将纹理连进来，保存asset，关闭再打开，才能正常工作。
![](image/2021-06-12-21-41-36.png)

# Input

## boolean
可以用一个branch节点来区分两个不同的输入，true就输出x， false就输出y。
![](image/2021-06-12-21-44-29.png)

## color

## constant数学常数
![](image/2021-06-12-21-45-36.png)

## integer

## slider

## time
记录了从开始到现在的时间
![](image/2021-06-12-21-47-29.png)

## 几何

### Bitangent vector双切线
![](image/2021-06-12-21-50-23.png)

### Normalvector顶点法线
![](image/2021-06-12-21-50-52.png)

### position顶点位置
### Screen position屏幕空间的顶点位置
### tangent vector 切线向量
### UV
### vector color顶点的默认颜色
### view direction相机方向

## Gradient渐变
![](image/2021-06-12-21-54-30.png)
![](image/2021-06-12-21-54-48.png)

## 光照

### ambient环境光
![](image/2021-06-12-21-55-59.png)

### baked烘培
烘焙进全局光照
![](image/2021-06-12-21-57-01.png)

### reflection probe反射探针

## 矩阵
![](image/2021-06-12-21-57-51.png)

### transformation Matrix（MVP矩阵）
![](image/2021-06-12-21-59-20.png)

## PBR

### Dielectric Specular电介质镜面
![](image/2021-06-12-22-01-02.png)

### metal reflectance金属反射率
![](image/2021-06-12-22-02-06.png)

## 场景

### camera
![](image/2021-06-12-22-03-10.png)

### fog

### object对象本身
![](image/2021-06-12-22-08-33.png)
### scene color场景颜色

### Scene depth

### screen屏幕
![](image/2021-06-12-22-09-39.png)

## Textrue
textrue节点总是以一对出现

### Cubemap Asset 和 Sample Cubemap
![](image/2021-06-12-22-11-09.png)

### Texture 2D asset 和 Sample texture 2D
![](image/2021-06-12-22-11-54.png)

### Texture 2D Array Asset
纹理数组，通过索引访问其中一个
![](image/2021-06-12-22-12-54.png)

### Texture 3D Asset
![](image/2021-06-12-22-14-01.png)

### Sampler State采样状态
可以帮助导入纹理
![](image/2021-06-12-22-15-33.png)
![](image/2021-06-12-22-15-39.png)

### Texel size像素大小
可以改变分辨率


# Master
master节点可以访问PBR和unlit
![](image/2021-06-13-20-18-45.png)

# Math
## absolute绝对值

## Exponential指数
## length向量的模
## log
## Modulo取余
## Negate取反
## Normalize
## posterize色调分离
将连续的颜色拆成阶梯状
![](image/2021-06-13-20-26-48.png)
![](image/2021-06-13-20-26-31.png)

## Reciprocal取倒数
## Reciprocal Square Root倒数平方根

## add加
## subtract减
## divide除
## Multiple乘
## Power幂指数
## Square root平方根

## DDX 对x求导
## DDY
## DDXY

## 插值
### lerp线性插值
### inverse Lerp
逆转插值结果，得到T的值
![](image/2021-06-13-20-39-41.png)
### smoothstep
## 矩阵
### Matrix Construction构造矩阵
![](image/2021-06-13-20-41-10.png)
### Matrix Determinant行列式
### Matrix Split分离矩阵的行或列
![](image/2021-06-13-20-42-31.png)
### Matrix Transpose转置矩阵
## 范围Range
### clamp
将输入值限定在最小值和最大值之间
### Fraction小数部分
### Maximum
### Minimum
### One minus

![](image/2021-06-13-20-45-59.png)
### Random Range随机数
基于种子生成一个最小值和最大值之间的浮点数
![](image/2021-06-13-20-46-53.png)

### Remap映射
将一个范围的数映射到另一个范围
![](image/2021-06-13-20-47-54.png)

### Saturate
将输入值限定在0到1。

## Round近似

### ceiling向上取整
### florr向下取整
### Round四舍五入
### sign输出正负号
### step
输入一个阈值edge，小于edge的输出0，大于edge的输出1
![](image/2021-06-13-20-51-53.png)

## 三角函数
![](image/2021-06-13-20-53-00.png)

### Degrees To Radians
角度转为弧度
### Radians To Degrees
## 向量
### distance
### Dot Product
### Cross Product

### 菲涅尔项
![](image/2021-06-13-20-55-22.png)
### Sphere Mask
### Ratote About Axis按轴旋转
### Reflection反射方向
### Projection投影
### transform切换坐标空间
求模型空间中的原点，在世界空间下的坐标
![](image/2021-06-13-21-01-18.png)

## Wave波
### Noise Sine Wave正弦波
### Sawtooth Wave锯齿波
![](image/2021-06-13-21-17-48.png)
![](image/2021-06-13-21-18-00.png)
### Square Wave方形波

![](image/2021-06-13-21-18-25.png)
### Triangle Wave三角形波
![](image/2021-06-13-21-19-10.png)
# Procedual程序化纹理
## Checkrboard棋盘

![](image/2021-06-13-21-20-21.png)
## Noise

![](image/2021-06-13-21-21-07.png)
## Shape几何图形
可以用它们来做遮罩
### ellipse椭圆
### polygon多边形
### Rectangle矩形
### Rounded Rectangle圆角矩形

![](image/2021-06-13-21-23-23.png)
![](image/2021-06-13-21-23-42.png)

# Util
## preview预览
可以输入任何东西，并且只显示颜色
![](image/2021-06-13-21-25-04.png)

## logic逻辑运算符
![](image/2021-06-13-21-25-52.png)

### Is infinite是否无穷
### Is Front Face是否是正面
如果想要使用这个节点，必须回到PBR Master中设置双向渲染
![](image/2021-06-13-21-27-40.png)

### Comparison比较两个数

### branch分支
打勾就输出True的内容，否则相反。
![](image/2021-06-13-21-29-54.png)

# UV
## flipbook序列帧动画

![](image/2021-06-13-21-31-48.png)
![](image/2021-06-13-21-31-55.png)

## Polar Coordinates极坐标
![](image/2021-06-13-21-32-42.png)

## radial Shear径向剪切
就像在材质上有一个无形的球，
![](image/2021-06-13-21-34-05.png)

## Rotate旋转
![](image/2021-06-13-21-34-41.png)

## Spherize
![](image/2021-06-13-21-35-33.png)

## tilling and offset平铺和偏移
![](image/2021-06-13-21-36-44.png)

## Twirl旋涡
![](image/2021-06-13-21-37-50.png)

## Triplanar
![](image/2021-06-13-21-39-19.png)











