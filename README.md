# 4D-WWW-Cache
Static caching for 4D

##Usage

### Set a Cache
```
Example 1:
$cache_is_set:=_w3c_set_cache ($url;$body)

Example 2:
$endpoint:="http://www.james.borillo.com"
$http_status:=HTTP Get($endpoint;$response)
$cache_is_set:=_w3c_set_cache ($endpoint;$response)

```

### Get a Cache
```
$txt:=_w3c_get_cache("http://www.jamesborillo.com")

```