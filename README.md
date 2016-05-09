# angular-webuploader

[webuploader](http://fex.baidu.com/webuploader) It's a new file uploader solution!

本项目是使用angular指令封装的webuploader demo，弹窗上传图片，缩略图展示列表，翻页效果；支持点击缩略图查看大图详情；

## ScreenShot

![screenshot0](https://raw.githubusercontent.com/giscafer/angular-webuploader/master/images/screenshot.png)

![screenshot1](https://raw.githubusercontent.com/giscafer/angular-webuploader/master/images/screenshot2.png)

![screenshot2](https://raw.githubusercontent.com/giscafer/angular-webuploader/master/images/screenshot1.png)

## Usage

本demo没有给出java后台代码，后台代码也简单，一个文件读写+图片压缩，返回结果参考以下`json`格式；
然后将图片上传接口请求地址在`app.js`配置后即可。

```javascript
	
	{
		"status":true,//上传成功状态
		"newName":"/test/temp/upload/picture/20160422/c0c0b8f7bc574ec88f891ff834b79bab.jpg",//原图片路径
		"thumbName":"/test/temp/upload/picture/20160422/thumb/c0c0b8f7bc574ec88f891ff834b79bab.jpg"//缩略图路径
	}


```

## License
![](https://img.shields.io/badge/license-MIT-blue.svg)

---

> [giscafer.com](http://giscafer.com) &nbsp;&middot;&nbsp;
> GitHub [@giscafer](https://github.com/giscafer) &nbsp;&middot;&nbsp;
> Weibo [@Nickbing Lao](https://weibo.com/laohoubin)