## Python 爬取段友之家贴吧图片和小视频
### 爬取这些网站里的数据主要用的模块bs4，requests以及os，都是常用模块。
### 大概思路就是通过requests模块请求网页html数据，然后通过bs4模块下的BeautifulSoup分析请求的网页，然后通过css查找器查找内涵段子的图片以及小视频的地址。