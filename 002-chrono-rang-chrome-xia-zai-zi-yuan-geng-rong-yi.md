众所周知, chrome原生的下载功能并不好用, 以查看下载任务为例, 我们需要点击两次(点击右上角 **三个点** , 点击**下载内容**) 才能查看当前的任务

> ![](https://user-gold-cdn.xitu.io/2019/5/3/16a7c3f7d624ff35?w=1062&h=856&f=png&s=145956)
而使用了chrono, 只需要点击一次

> ![](https://user-gold-cdn.xitu.io/2019/5/3/16a7c3f7d65984bf?w=1240&h=1232&f=png&s=149532)

## chrono还集成了一些超赞的功能, 可以按照"资源大小", 进行嗅探过滤!
> chrono可以对浏览器可见的页面进行**资源嗅探**, 并批量下载静态资源, 相当于爬虫,如果你是一个设计师, 对批量下载图片情有独钟, 又懒得写爬虫程序, 这个"资源嗅探"的功能或许能提升你下载图片的效率

> ![](https://user-gold-cdn.xitu.io/2019/5/3/16a7c3f7d6a7b3cc?w=1240&h=697&f=png&s=607544)

### 以抓取behance的图片为例
- 切换至资源嗅探器
> ![](https://user-gold-cdn.xitu.io/2019/5/3/16a7c3f7d6bd24b2?w=972&h=542&f=png&s=124958)

- 按照图片的空间尺寸, 过滤图片

> ![](https://user-gold-cdn.xitu.io/2019/5/3/16a7c3f7d688140c?w=1240&h=812&f=png&s=624287)

> - 如果你的页面为懒加载(网页根据用户鼠标的滚动, 动态加载图片), 嗅探器会根据页面加载图片数量的变化, 自动添加新图片到嗅探列表
> - 过滤文件的尺寸可以设置的稍微大一些(比如200kb以上), 这样可以筛选出, 质量较高的图片
- 批量勾选需要下载的图片, 开始下载

> ![](https://user-gold-cdn.xitu.io/2019/5/3/16a7c3f7d6c900d8?w=1240&h=765&f=png&s=613625)

> 可以批量勾选图片, 也可单独勾选图片, 如果你懂正则, 还可以添加正则表达式来过滤图片(正则一般是留给程序员玩的...)
- 批量下载成功的图片
> ![](https://user-gold-cdn.xitu.io/2019/5/3/16a7c3f84f4375f4?w=1240&h=701&f=png&s=733958)

> 建议适当提高过滤图片尺寸的标准, 获得尺寸更大, 质量更高的图片(以上展示的图片筛选条件为大于200kb)



## 小结:
- chrono是一个很好用的工具, 按照资源的大小来进行筛选, 的确是很巧妙的功能!
- chrono的下载图片的速度很快, chrono充分利用了chrome已经下载的资源,按照用户定义的规则, 批量将浏览器已经下载好的图片, 保存到本地
- chrono不只是可以下载图片, 凡是提供下载链接的, chrono都可以下载, 可以完全替代chrome原生的下载


## 插件下载地址
https://chrome.google.com/webstore/detail/chrono-download-manager/mciiogijehkdemklbdcbfkefimifhecn?hl=zh-CN

---

## 写在最后(我需要你的支持)
- 本文属于**Chrome插件英雄榜** 项目的一部分, 项目Github地址: [https://github.com/zhaoolee/ChromeAppHeroes](https://github.com/zhaoolee/ChromeAppHeroes)

- **Chrome插件英雄榜**, 为优秀的Chrome插件写一本中文说明书, 让Chrome插件英雄们造福人类, 如果你喜欢这个项目, 希望你能为本项目添加一颗 🌟星.

- ChromeAppHeroes, Write a Chinese manual for the excellent Chrome plugin, let the Chrome plugin heroes benefit the human, If you like this project, I hope you can add a star 🌟 to this project.

