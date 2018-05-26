# hello-world
just for training
rm(list=ls())
library(rJava)
library(xlsx)     #读表
library(plyr)
library(dplyr)   #截取   很强大
#s神经网络
library(Rcpp)#与RSNNS关联
library(RSNNS)#涉及到神经网络中的其它拓扑结构和网络模型
#Stuttgart Neural Network Simulator（SNNS）是德国斯图加特大学开发的优秀神经网络仿真软件
library(nnet)#提供了最常见的前馈反向传播神经网络算法
library(AMORE)#提供了更为丰富的控制参数，并可以增加多个隐藏层
library(neuralnet)#提供了弹性反向传播算法和更多的激活函数形式
library(autoencoder)
library(deepnet)#实现了一些Deep Learning结构和Neural Network相关算法，
#数据包络模型
library(lpSolveAPI)   #这些包要用R的32位操作系统
library(ucminf)
library(Benchmarking)
library(bootstrap)
library(TFDEA)

#在execl表格中圈住想要读取的数据部分，选择“复制”，
#在R中执行命令read.table("clipboard")可以直接读出选中的数据
#d<-read.table("clipboard")  
