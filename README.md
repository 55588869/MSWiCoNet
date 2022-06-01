# 多阶段宽上下文网络
一个用于遥感图像的语义分割网络模型，支持的数据集为BLU和Potsdam数据集。
## 环境配置
conda create -n xxx python=3.7 -y
conda activate xxx
pip install -r requirements.txt
###requirements.txt
```bash
scikit-image
opencv-python
matplotlib
torchvision
tensorboardX
```
##**使用方法**

BLU数据集训练运行Train_BLU.py文件

Potsdam数据集训练运行Train_PD.py文件

模型测试运行相应的Eval.py文件

Display_main文件是一个制作好的界面，能够对输入图片进行预测并展示输入图片和模型的预测结果

BLU数据集位于BLU文件夹下，Potsdam数据集位于PD文件夹下

模型训练好的参数位于checkpoints文件夹下
