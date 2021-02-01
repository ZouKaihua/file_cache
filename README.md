# file_cache
file cache by imitating redis from dj for personal usage

```python
from file_cache.cache import FileCache
cache = FileCache(dir='/var/tmp/file_cache', params={})
cache.set("zkh_cache", "zkh_cache", 5)
cache.get("zkh_cache", "")
```
