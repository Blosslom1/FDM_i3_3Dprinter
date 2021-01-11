# 3Dimension Printer

## 零部件介绍

### X型材

这次打印机项目使用的框架是欧标2020铝合金型材，银色的市场价格是9.5-12每米，黑色的价格是12以上每米，制作需要切割指定长度的型材，具体情况如下表

| x轴  | 250mm |
| ---- | ----- |
| y轴  | 390mm |
| z轴  | 320mm |
| 横梁 | 400mm |

在购买材料时，x,y,z都需要两个，横梁只需要采购一个。具体结构如下图：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/1.jpg)

图中所有尺寸都是标准欧标2020铝型材，他们之间需要使用到角码进行连接，我使用的角码是下图角码

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/2.jpg)

在对应位置还需要有配套的固定螺丝，例如Y轴42步进电机固定需要T型螺母。螺母规格如下图：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/3.jpg)

L=10，H=5，S=6，D=M3，主要是L的型号必须对上，D可以根据螺丝选取，螺丝选取规格如下图：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/4.jpg)

S=2，t=1，dk=6，d=M3，L可以多种规格。

### 光轴

光轴的作用就是相当于导轨，选用的的导轨是8mm直径的，运动滑块需要在导轨上运动带动打印头移动，导轨还需要有滑动轴承配和。

光轴的价格大概是16元每米。这个只是大概价格，实际购买中都是有一定规格选取的。

| x光轴 | 350mm |
| ----- | ----- |
| y光轴 | 390mm |
| z光轴 | 350mm |

滑动轴承选用的是LM8LUU，市场价格在1.4一个，规格如下图：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/5.jpg)

高度=24，外径=15，内径=8。其中加长的高度是45mm

### 丝杆

丝杆是Z轴向的传动装置，在丝杆螺母的带动下，位于Z轴的模块会沿着丝杆滑动，带动打印头在Z轴向移动，同时他也控制升高的精度，而升高的精度会影响打印精度，丝杆会成为一小部分影响因素。丝杆和丝杆螺母的构造图如下：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/6.jpg)

该机器采用丝杆导成为8，长度为350。

### 联轴器

联轴器使用很简单就是将丝杆和42步进电机进行连接。购买的是5*8联轴器，市场价格2块左右。结构图如下。

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/7.jpg)

### 42步进电机

之所以叫做42步进电机是因为他的长宽都是42mm，42步进电机有很多规格，主要区别是在高度上面，高度越高扭力越大，打印可调速度就越快。本打印机中Y轴使用48mm高步进电机，Z和X使用38高步进电机。挤出机使用泰坦步进电机。结构图如下：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/8.jpg)

### 同步轮&惰轮

同步轮是用来固定在步进电机上的，它是用来传动的一个齿轮，常见的有16齿和20齿，选用的是20齿。可以根据需求进行选择，个人认为18齿倾向于打印精度，20齿倾向与打印速度。价格大概1.5元一个，结构图如下：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/9.jpg)

惰轮是一个从动轮，价格在2元左右一个结构如下：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/10.jpg)

同步带是等于传动带，价格大概2元每米。

### 滚动轴承

滚动轴承型号很多，这里采购它的作用是在丝杆固定使用这个更好的转动。市场价格在0.5元左右，购买的是内径8直径22高7型号是608ZZ

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/11.jpg)

### 散热管

散热管是套在喉管外面，对喉管进行散热的。市场价格在4元左右。我这里设计的是远程挤出，散热管是使用的CR8的具体如图：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/12.jpg)

### 铁氟龙管

因为远程挤出耗材，所以必须要使用铁氟龙管作为耗材引导，防止耗材在进出时弯曲变性。铁氟龙管价格在2~3元每米。

### 气动插头

用在散热管和铁氟龙管连接处接口是M6内径大于4mm，市场价格1元左右。具体形状如图：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/13.jpg)

### 远程挤出机

远程挤出机由挤出装置和步进电机组成，原设计采用泰坦挤出机专用步进电机。挤出机型号是CR10，价格为11元，构造如图所示：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/14.jpg)

### 铝加热块

加热块是连接电热管和喉管及喷头的，用来传热熔化耗材。选用型号E3D，价格随质量变化，我购买的是0.45元的我觉得没必要买太好的。规格如下图：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/15.jpg)

### 散热风扇

和CPU散热风扇同理，散热用的，大概2元一个，规格是40\*10*10我准备安装两个，但是模型设计的只有一个，因为要等装好后自己打印自己的配件。

### 喉管

喉管是引导耗材熔化的，喉管种类很多，和散热配套的是E3D单价0.5元，规格图如下：

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/16.jpg)

### 加热管

是热源产生热量的主要部件，加热的温度全部靠它产出，价格也随质量波动较大，购买的是2元左右的。

### 热敏电阻

监控温度，调节加热管发热量。价格在1元左右

### 喷头

进出材料的头，精度有多种规格，常见的有0.2~0.8mm。黄铜的价格大概也就几毛钱一个。

## 固定件介绍

所有的尺寸单位均为in，由于没有更改默认单位。

### X固定

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/17.jpg)

### X固定右

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/18.jpg)

### Y固定上

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/19.jpg)

### Y光轴固定

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/20.jpg)

### Y同步轮固定

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/21.jpg)

### Y轴步进电机固定

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/22.jpg)

### Z轴固定

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/23.jpg)

### 底座

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/24.jpg)

### 电源支座

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/25.jpg)

### 挤出机支架

![](https://cdn.jsdelivr.net/gh/Blosslom1/img1@master/3dimensions/26.jpg)

建模部分到这里基本结束，模型开源到github，**[点击下载]()**

## 程序固件


$$
Prepare
\begin{cases}
Move \ axis
\begin{cases}
Move X
\begin{cases}
Move \ 10mm\\
Move \ 1mm\\
Move \ 0.1mm\\ 
\end{cases}\\
Move Y
\begin{cases}
Move \ 10mm\\
Move \ 1mm\\
Move \ 0.1mm\\ 
\end{cases}\\
Move Z
\begin{cases}
Move \ 10mm\\
Move \ 1mm\\
Move \ 0.1mm\\ 
\end{cases}\\

Extruder
\begin{cases}
Move \ 10mm\\
Move \ 1mm\\
Move \ 0.1mm\\ 
\end{cases}
\end{cases}\\
Auto \ home
\end{cases}
$$






















