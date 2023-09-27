ViT工程文件夹为主要实验模型。训练后工程文件打包有3G多无法上传邮件，需要先训练
训练：运行train.py等待模型训练
预测：运行predict.py
  目录：
  --flops.py
  --my_dataset.py
  --predict.py    //预测脚本
  --train.py      //训练脚本
  --utils.py   
  --vit_model.py  //主要模型文件
  --flower_photos //训练样本
    --daisy
    --dandelion
    --roses
    --sunflowers
    --tulips
  --weights       //训练生成的模型结果
  --test1.jpg     //测试图片
  --jx_vit_base_patch16_224_in21k-e5005f0a.pth   //预训练模型权重文件

ResNet文件夹为对比实验代码，代码较少，jupyter打开，自动拆分训练集测试集，仅作对比实验。
训练样本图片过多未上传，请联系我发送网盘链接