# Use below code and replace parameter

```py
import urllib 
import urllib2 

data = urllib.urlencode({"token":"Your-Token","action":"text","from":"919876*****","country":"91","to":"9876*****","text":"Sample Text Message","uid":"12324565"}) 

req = urllib2.Request('https://www.gogossip.live/api', data) 
response = urllib2.urlopen(req) 
result = response.read()
```
