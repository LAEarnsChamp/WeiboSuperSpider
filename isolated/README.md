# 作者简介


|作者|[inspurer](https://inspurer.github.io/2018/06/07/%E6%9C%88%E5%B0%8F%E6%B0%B4%E9%95%BF%E7%9A%84%E7%94%B1%E6%9D%A5/#more)|
|:---:|:---:|
|QQ交流群|[861016679](https://jq.qq.com/?_wv=1027&k=5Js6sKS)|
|个人博客|[https://inspurer.github.io/](https://inspurer.github.io/)|

# 2021/7/17 更新

**2021新版本微博超级爬虫来了**

<p align="center">

包括三个部分，微博话题爬虫，微博评论爬虫，微博转发爬虫，简介如下

微博话题爬虫可以根据关键词，按照时间段，爬取保存指定微博，出错了重新运行能继续抓取。

微博评论爬虫可以爬取想要的微博的评论，及其评论的回复，可以抓取上万条评论之多。

微博转发爬虫可以爬取微博的转发信息，以及转发微博的转发等，无限递归。
  
</p>

详细信息可以参考系列文章，地址如下：

[2021 新版微博话题爬虫发布
](https://mp.weixin.qq.com/s?__biz=MzUzMDE5MzQ3Ng==&mid=2247484943&idx=1&sn=b1c9520a388171932a9037dbd0ac5460&chksm=fa54cb24cd234232e62bec64881df16bcc1257b3e79628b57d562cd88ae9ffd91b883f15284d&scene=178&cur_album_id=1393531201285226497#rd)

[2021 新版微博评论及其子评论爬虫发布
](https://mp.weixin.qq.com/s?__biz=MzUzMDE5MzQ3Ng==&mid=2247484955&idx=1&sn=e328c1fc9b4dff844303c20cdce29fe2&chksm=fa54cb30cd234226a568a329191eb5d08d1078522f91c9d4c87bfb4fd7a43b824fb2991d0143&scene=178&cur_album_id=1393531201285226497#rd)

[2021 微博最新转发爬虫发布
](https://mp.weixin.qq.com/s?__biz=MzUzMDE5MzQ3Ng==&mid=2247484962&idx=1&sn=8cc9f9e2551cec71b244c9fae8bbbcd1&chksm=fa54cb09cd23421fd0703130c41998f1633e790758f98fa6b7610e9b14493606a3e729f3ec7f&scene=178&cur_album_id=1393531201285226497#rd)


后续更新，欢迎微信扫描下方二维码或者在微信内搜索 **微信公众号：月小水长（ID:inspurer)** 进行关注；

<p align="center">
  <img src="qrcode.jpg"></a>
</p>

# WeiboSuperScrapy
最强微博爬虫，用户、话题、评论一网打尽。

## GUI 功能集中版

运行 GUI.py 即可爬取用户/话题微博

运行 WeiboCommentScrapy.py 并修改里面的微博id (wid) 即可爬取指定微博的所有评论。

## 无 GUI 功能独立版

单独的 py 文件分别对立一个 功能

WeiboCommentScrapy.py 爬取评论

WeiboTopicScrapy.py   爬取指定关键词的所有微博，突破了 50 页的限制，可指定~截至日期~时间段搜索（比如 20200101-20200102）

WeiboSuperCommentScrapy.py 可爬取一条微博的所有评论，更为强大


## Reference

[https://www.jianshu.com/p/8dc04794e35f](https://www.jianshu.com/p/8dc04794e35f)
