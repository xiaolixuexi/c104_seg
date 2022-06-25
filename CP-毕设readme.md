### CP-毕设readme

* 数据集相关

> /media/c104/data/LtData

此目录下是所有的数据集，以后可以根据需要去使用



* 代码相关

> /home/c104/c104/LtCc

我所有的代码都在这个目录里，每一个都可以跑，虚拟环境可以根据

> conda env list

```
FactSeg                  /home/c104/anaconda3/envs/FactSeg
ICNET                    /home/c104/anaconda3/envs/ICNET
LJ                       /home/c104/anaconda3/envs/LJ
LoveDA                   /home/c104/anaconda3/envs/LoveDA
LoveDA-LtCc              /home/c104/anaconda3/envs/LoveDA-LtCc
LtCc-LoveDA              /home/c104/anaconda3/envs/LtCc-LoveDA
Trans_RS                 /home/c104/anaconda3/envs/Trans_RS
YOLOV5                   /home/c104/anaconda3/envs/YOLOV5

```

选用Trans_RS即可



/c104/LtCc/Trans_RS/Trans_Unet/TransUNet$ 

这个目录下有两个py文件

直接使用python执行即可，训练

> transunet_train.py 

预测：

bigmappredict.py

根据代码里的路径更改数据集的地址即可

可视化的一些东西可以使用tensorboard来显示

