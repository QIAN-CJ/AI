# AI
人工智能导论课程项目  
使用VGG19迁移学习实现图像风格迁移  
使用的语言为Python3.7  
框架为tensorflow2.0  
clone项目后需要安装依赖环境  
pip install -r requirements.txt  
修改settings.py中的配置参数，这里修改为共训练20个epoch，每个epoch训练100次  
运行训练脚本  
python train.py  
运行成功则会输出训练进度，训练完成后在输出目录（默认./output）下能看到生成的图片，默认每个 epoch 保存一次生成的图片。  
示例：  
内容图片  

![image](https://github.com/QIAN-CJ/AI/blob/main/samples/dog.jpg)  
风格图片

![image](https://github.com/QIAN-CJ/AI/blob/main/samples/style.jpg)  
生成图片

![image](https://github.com/QIAN-CJ/AI/blob/main/samples/dog_gen.jpg)
