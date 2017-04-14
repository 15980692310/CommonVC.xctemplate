# CommonVC.xctemplate
自定义Xcode类模板
## 创建类模板

## 介绍
#### 建立类模板的好处就是求同存异，模板式开发，统一规范，尽量做到类的结构一致。
先上图爽一波

![show.gif](http://upload-images.jianshu.io/upload_images/1304063-69bed1cc8c2ea731.gif?imageMogr2/auto-orient/strip)

## 做法
- 先找路径：/Applications/Xcode.app/Contents/Developer/Library/Xcode/Templates/File Templates/Source


![类模板路径.png](http://upload-images.jianshu.io/upload_images/1304063-7f955f5525b70a8c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 把下载的模板CommonVC.xctemplate，拖到这个路径下，如图:

![1.png](http://upload-images.jianshu.io/upload_images/1304063-5c2f67245301855e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 原理
类本身没什么，主要是里面有个TemplateInfo.plist需要了解一下
#### TemplateInfo.plist

![TemplateInfo.plist说明.png](http://upload-images.jianshu.io/upload_images/1304063-7c0152b08724eb0a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### Options中的Item0，Item1，Item2，Item3 对应第一行到第四行

![Options.png](http://upload-images.jianshu.io/upload_images/1304063-5edde055a65c9fbe.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### Options里Item选项说明


![Options中Item说明.png](http://upload-images.jianshu.io/upload_images/1304063-9808adf8b46aeaa8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)




#### TemplateIcon图片
图片是用来显示在New File的菜单上的，任意放一个自己喜欢的图片，像素138*138。

![2.png](http://upload-images.jianshu.io/upload_images/1304063-4c1a0b5ccfb085f2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
