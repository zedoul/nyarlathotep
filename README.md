nyarlathotep
============
Nyarlathotep is web-crawler in Python. 
The name 'Nyarlathotep' has its root in [the works of H.P.Lovecraft](http://en.wikipedia.org/wiki/Nyarlathotep)

Usage
=======
```python
import nyarlathotep
crawler = nyarlathotep.crawler('outergods.db')
chaos = ['http://en.wikipedia.org/wiki/Nyarlathotep']
crawler.crawl(chaos)
```

Prerequisite
========
BeautifulSoup
pysqlite2
