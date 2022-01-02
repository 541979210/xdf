<!-- TOC -->

- [Perspective-n-Point Background](#perspective-n-point-background)
    - [d-2d Epipolar geometryFundamental, Essential, Homography](#d-2d-epipolar-geometryfundamental-essential-homography)
    - [d-3d ICPIteration](#d-3d-icpiteration)
    - [d-3d PnPDLT, P3P, EPnP, UPnP](#d-3d-pnpdlt-p3p-epnp-upnp)
- [Several PnP Algorithm](#several-pnp-algorithm)
- [Code Analysis](#code-analysis)
- [Conclusion](#conclusion)

<!-- /TOC -->
# Perspective-n-Point Background

![](https://static01.imgkr.com/temp/8daf874c3a954dafb943af9a0211c564.png)

**注意四个坐标系（世界坐标系，相机坐标系，归一化坐标系，图像坐标系**）  
1.***世界坐标系到相机坐标系***  
![](https://static01.imgkr.com/temp/ceffaa0e944340639b44e53f11e32ca1.jpg)  
![](https://static01.imgkr.com/temp/422392e6f55c44ee8a39730a4996dd49.png)
> 旋转的正方向是指从轴的正往负看，逆时针为正   

2.***相机坐标系到像平面坐标系***     
![](https://static01.imgkr.com/temp/220a2ab43f184c8abb8e04d2d2cd52c1.png)  
可得到公式  
![](https://static01.imgkr.com/temp/63ec409eedab480b9deca079d2701642.png)  
3.***像平面到图像坐标系***    
![](https://static01.imgkr.com/temp/48bb4b8417f441b597a624f0e72161ca.png)  



## 2d-2d Epipolar geometry(Fundamental, Essential, Homography)

## 3d-3d ICP(Iteration)

## 2d-3d PnP(DLT, P3P, EPnP, UPnP)

![](https://static01.imgkr.com/temp/e108fe53f6ea4fd3ad32593c1747bd69.png)

# Several PnP Algorithm

- P3P
![](https://static01.imgkr.com/temp/0bf0595b90f24c1e9987cdf7753c0e9b.png)

- EPnP
- DLT
- UPnP
- MRE(LS Iteration, G2O)

# Code Analysis

# Conclusion
