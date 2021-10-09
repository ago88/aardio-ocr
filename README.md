# 简易OCR文字识别工具

#### 介绍
一款调用百度高精度文字识别API的简易OCR工具，直接调用微信截图DLL实现截图功能

#### 软件界面
![输入图片说明](https://raw.githubusercontent.com/ago88/aardio-ocr/master/res/introduce.png "简易OCR文字识别工具")

#### 代码说明
1.  PrScrn.dll 为微信截图动态链接库，可直接将PC微信目录下此文件拷贝过来使用，已打包到应用中
2.  二维码识别为扩展库zbar,直接调用即可

#### 使用说明
1.  请自行注册百度KEY，填下后保存即可。（密钥保存位置在 %appdata% 下）
2.  文字图片也可直接拖拽到软件上进行识别
