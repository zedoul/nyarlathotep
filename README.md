Nyarlathotep
============
Nyarlathotep is web-crawler in Python. 
The name 'Nyarlathotep' has its root in [the works of H.P.Lovecraft](http://en.wikipedia.org/wiki/Nyarlathotep)

What's more, generous nyarlathotep has simple [PageRank](http://en.wikipedia.org/wiki/PageRank) feature.

Usage
=======
```python
import nyarlathotep
crawler=nyarlathotep('searchindex.db')
crawler.createindextables()
chaos = ['http://en.wikipedia.org/wiki/Main_Page']
crawler.crawling(chaos)
crawler.calculatepagerank()
```

Prerequisite
========
- BeautifulSoup
- pysqlite2
