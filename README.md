# facenet-demo

## 数据准备：

①lfw数据集（lfw），bdyun下载：

链接：https://pan.baidu.com/s/1b9gLUEK8NqEiKGzkv0z26Q

提取码：2mhn 

存放于 facenet/data

![image](https://github.com/1024210879/facenet-demo/blob/master/data/images/path_lfw.jpg)

②facenet预训练权重（20170512-110547.pb），bdyun下载：

链接：https://pan.baidu.com/s/1iJjb_45czF5v_cE4uSl24g

提取码：iqhm

存放于 facenet/weight

![image](https://github.com/1024210879/facenet-demo/blob/master/data/images/path_weight.jpg)

③facenet预训练pkl文件（classifier.pkl）bdyun下载：

链接：https://pan.baidu.com/s/1TiiRBWxX8a0Kc5ciahmRxg

提取码：oos2

存放于 facenet/weight

![image](https://github.com/1024210879/facenet-demo/blob/master/data/images/path_pkl.jpg)

## 运行环境

win10，python3.6.3

运行 bat_init_env.bat 下载依赖库

## demo使用

#### 运行 bat_align_dataset_mtcnn.bat 人脸对齐 生成 data/lfw_160

#### 运行 bat_detect_face_images.bat 静态图人脸检测、人脸关键点检测

#### 运行 bat_detect_face_camera.bat 摄像头人脸检测、人脸关键点检测

#### 运行 bat_compare.bat 人脸对比

#### 运行 bat_cluster.bat 人脸聚类

#### 运行 bat_predict.bat 在人脸库查找某个人脸

#### 运行 bat_train_tripletloss.bat 训练网络
