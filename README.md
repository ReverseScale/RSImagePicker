# RSImagePicker
简单的使用图片选择器

![](https://img.shields.io/badge/platform-iOS-red.svg) 
![](https://img.shields.io/badge/language-Objective--C-orange.svg) 
![](https://img.shields.io/badge/download-791K-brightgreen.svg)
![](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg) 

一个使用简单的图片选择工具，封装回调一个结果图片，支持系统级编辑功能。

| 名称 |1.列表页 |2.展示页 |3.结果页 |
| ------------- | ------------- | ------------- | ------------- |
| 截图 | ![](http://og1yl0w9z.bkt.clouddn.com/17-7-31/32630800.jpg) | ![](http://og1yl0w9z.bkt.clouddn.com/17-7-31/99434463.jpg) | ![](http://og1yl0w9z.bkt.clouddn.com/17-7-31/83425022.jpg) |
| 描述 | 通过 storyboard 搭建基本框架 | 选择图片前 | 选择图片后 |


## Advantage 框架的优势
* 1.文件少，代码简洁
* 2.不依赖任何其他第三方库
* 3.同时支持本地图片和拍摄图片
* 4.具备较高封装性


## Requirements 要求
* iOS 7+
* Xcode 8+


## Usage 使用方法
### 第一步 引入头文件
```
#import "RSImagePicker.h"
```
### 第二步 简单调用
```
[RSImagePicker showImagePickerFromViewController:self allowsEditing:YES finishAction:^(UIImage *image) {
    if (image) {
        [sender setImage:image forState:UIControlStateNormal];
    }
}];
```

使用简单、效率高效、进程安全~~~如果你有更好的建议,希望不吝赐教!


## License 许可证
RSImagePicker 使用 MIT 许可证，详情见 LICENSE 文件。


## Contact 联系方式:
* WeChat : WhatsXie
* Email : ReverseScale@iCloud.com
* Blog : https://reversescale.github.io
