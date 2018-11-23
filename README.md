# 集群配置

## 硬件配置

MU01为管理节点，其/home与/opt被所有节点共享。

CU01、CU02各拥有2个K80 Nvidia显卡。

CU03-CU07拥有特制的CPU芯片，也可用来完成计算任务。

## 环境配置

CU01默认计算环境为 CUDA 8 + python3.6 + tensorflow-gpu 1.4（包括其他keras等库）

CU02默认计算环境为 CUDA 9 + anaconda python3.56 + tensorflow-gpu 1.11（包括其他keras等库）

CU03-CU08默认计算环境为 anaconda python3.56 + tensorflow 1.11（包括其他keras等库）

## 其他

目前服务器处于非常状态，可向我要公共账号访问。

需要其他信息或者需要安装别的python库、公用软件可以发issue或者跟我本人说。
