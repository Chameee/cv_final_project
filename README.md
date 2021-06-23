# Computer Vision Final Project

这是计算机视觉期末PJ的 repo，主要工作为对比了在相同参数量/ FLOPs 的情况下。基于 Transformer 和 Convolution 的模型在单个数据集上的训练效率。所有代码都整合在 jupyter notebook 中，可以直接在 

Google Colab 中复现。

## 在 Colab 中打开

- 为了测试和调试模型方便，**不要忘记**手动在 Google Colab 的运行实例中上传测试用的 [cat.jpg](https://github.com/Chameee/cv_final_project/blob/master/cat.png)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uTSmhaCiT4_Hj3G3YHQA4QKVp5uitvrV?usp=sharing)


## 预训练模型

为了节约时间，你可以在[这里](https://drive.google.com/drive/folders/1ZdNCnoGhFuFAVdPA0W2z2mtLcftnLAJ2?usp=sharing)下载并导入我训练好的模型 。

### 使用方法

下载到本地后上传至 Colab 的运行实例，在 notebook 中输入

```
vit_model = torch.load('./vit_model_epo5.pth')
```

导入 ViT 的预训练模型，另外两个同理
