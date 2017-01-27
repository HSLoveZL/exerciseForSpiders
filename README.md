#SpiderStudy   
##About Item:   

    Item是保存爬取到的数据的容器   
```Python   
    import scrapy

    class DomozItem(scrapy.Item):
        title = scrapy.Field()
        link = scrapy.Field()
        desc = scrapy.Field()   
```
##默认的Scrapy项目结构   
   scrapy.cfg存放的目录被认为是*项目的根目录*。该文件中包含了Python模快名的字段定义了项目的设置。
