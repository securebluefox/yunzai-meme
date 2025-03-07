# yunzai-meme
![3F53077B8088F0C03FA7C81B2E4CC62A](https://user-images.githubusercontent.com/21212372/228231810-3202ff31-e5ed-4ab8-a93f-a55ab6d48f58.gif)

基于meme-generator的Yunzai机器人的表情包插件

## 可选
提供了一个默认的免费API，是作者的小鸡，可能生成比较慢。要求高的建议自己搭建，然后修改第6行的baseUrl为你的自建meme api，参考[这里](https://github.com/MeetWq/meme-generator)搭建。可选加入[扩展包](https://github.com/MeetWq/meme-generator-contrib)

更新：提供了一个docker镜像，一键搭建：`docker run -d -p 2233:2233 --restart=always geyinchi/meme-generator:latest`

更新：ARM版镜像，由@Regalia提供：`regaliaf/meme-generator`

要求不高或者没条件可以用内置的API。

## 安装

直接把meme.js扔到plugins/example目录下即可

## 食用方法

使用`meme帮助`查看帮助

建议先查看https://github.com/MeetWq/meme-generator 了解支持的表情包及合成要求。

需要图片合成表情包的可以通过回复、艾特（取头像）、默认（自己的头像）获取素材图片

需要文字合成表情包的需要在指令中添加文字，并用/隔开，如：可达鸭我爱你/你爱我

> 如果觉得有帮助，请帮我点一个免费的Star，谢谢！

## 致谢

* https://github.com/MeetWq/meme-generator
* https://github.com/MeetWq/meme-generator-contrib
