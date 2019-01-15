基于scrapy的校花网图片爬虫
### 需求
1.http://www.xiaohuar.com/hua 请求第一页。第一页每一个图集链接获取下来
2.图集详情页，点击相册
3.图集画廊页，相册下所有图片按照图片名保存。
### 步骤
1.scrapy startproject xiaohua_spidercom
2.scrapy genspider xiaohua xiaohuar.
3.开发
4.检查图片是否正常下载
