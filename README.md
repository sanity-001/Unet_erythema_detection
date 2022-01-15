# Unet_erythema_detection
A basic neural network for image segmentation.

## 前期准备
1.在logs文件夹中下载h5权重文件，百度网盘链接在logs文件夹中

2.将所有原图![image](https://user-images.githubusercontent.com/61897026/149626311-5ac4270f-c4e2-484c-bf2e-d74a0a9809cc.png)
放置在“/dataset_1/JPEGImages/”文件夹中，将json转换的所有图片![image](https://user-images.githubusercontent.com/61897026/149626394-971bc934-d979-4452-b29b-63100f652735.png)
放置在“/dataset_1/SegmentationClass/”文件夹中

## 搭载Colab使用
1. 注册谷歌账号，进入谷歌云端硬盘
2. 上传文件夹，进入后新建一个 ==Google Colaboratory==
![image](https://user-images.githubusercontent.com/61897026/149624698-35ae994d-3efa-4f00-892a-4c11bcb49990.png)
![image](https://user-images.githubusercontent.com/61897026/149624762-db310230-78fe-4e9c-ad4c-cc64f44fc357.png)
3.设置GPU：菜单栏——代码执行程序——更改运行时类型——选择GPU、
![image](https://user-images.githubusercontent.com/61897026/149624838-c7c963a3-3540-44fa-be73-718dcc677ed0.png)
4.连接谷歌云端文件夹
![image](https://user-images.githubusercontent.com/61897026/149624857-c37afd05-f9bb-48a8-bca0-024f3869f5b4.png)
5.运行训练程序
![image](https://user-images.githubusercontent.com/61897026/149624872-abd36339-a971-4dd3-95fd-522dd417562f.png)
6.预测红斑区域
![image](https://user-images.githubusercontent.com/61897026/149624898-d4b1500e-f686-4e04-a339-f59d53e1c008.png)
==若有报错“找不到改文件”，需要复制.py文件完整路径再运行==

## 注意事项
train.py里数据集的路径根据每个人电脑上colab中dataset_1文件夹的路径不同进行修改





