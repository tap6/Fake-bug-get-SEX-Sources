## 开发介绍
> 开发者：tap6 

> 程序语言：易语言

> 开发周期：两天的课余时间

> 开发完毕日期：2017-12-15


用了精易模块。软件思路是取出黄网所有栏目的链接，再获取某一栏目里所有存在视频列表的分页面，再获取某一分页面的所有视频页面链接，再进入视频页面链接获取片名和下载地址。再以追加的形式写出当前取得的片的下载地址。

源码码长了，看起来感觉有点乱，没啥学习意义，运行可以直接跑数据，有需要的朋友下载使用便是。

由于网站运行存在不确定性，网站啥时候换域名或者倒闭了都不知道，这个当框架改改同类型的网站应该还是能用的。

2017-12-21 运行代码跑出13448部小电影(各种类型)，我把爬下的数据放在了“我用爬虫爬下的数据”文件夹里，免得你们再爬一次。


###爬下来的数据格式是：

>电影1的名字
>电影1的图片
>电影1的下载地址

>电影2的名字
>电影2的图片
>电影2的下载地址

>电影3的名字
>电影3的图片
>电影3的下载地址