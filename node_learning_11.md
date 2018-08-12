```
　　很多人都有做数据采集的需求，用不同的语言，不同的方式都能实现，

　　用nodejs写采集程序还是比较有效率（可能也只是相对C#来说），
  今天主要用一个示例来说一下使用nodejs实现数据采集器，主要使用到request和cheerio。

 

　　request :用于http请求

　　https://github.com/request/request

　　cheerio:用于提取request返回的html中需要的信息（和jquery用法一致）

　　https://github.com/cheeriojs/cheerio

 

示例
　　单独去说API用法没什么意思也没必要记住全部API，下面开始示例

 

　　还是说点闲话：

　　nodejs开发工具还是很多，以前我也很推荐sublime，自从微软推出了Visual Studio Code后就转用它去做nodejs开发。

　　用它开发还是比较舒服的，免配置、启动快、自动补全、查看定义和引用、搜索快等，有VS的一贯风格，应该会越做越好，所以推荐一下^_^!

 

　　示例要求

　　从 http://36kr.com/ 中抓取其中文章的“标题”、“地址”、“发布时间”、“封面图片”

 

　　采集器

　　1.建立项目文件夹sampleDAU

　　2.建立package.json文件 
```
