## demo_test
### single keyword
```python
from bbc_news_spider import BBCNewsKeywordSearch
search_worker = BBCNewsKeywordSearch()
search_worker.setKeyword("mykeyword")
search_worker.crawl()
```

### batch keyword

```python
from bbc_news_spider import BBCNewsKeywordSearch
search_worker = BBCNewsKeywordSearch()
keywords = ['mykeword1', 'mykeyword2', 'mukeyword3']
search_worker.setKeywordListandRun(keywords)
```