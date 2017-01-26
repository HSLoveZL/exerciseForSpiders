#SpiderStudy   
###About Item:   
***
    Item是保存爬取到的数据的容器   
```Python   
    **import scrapy**
    
    class DomozItem(scrapy.Item):
        title = scrapy.Field()
        link = scrapy.Field()
        desc = scrapy.Field()   
```
