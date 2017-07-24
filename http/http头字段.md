### http协议

##### 什么http协议
    超文本传输协议（HTTP，HyperText Transfer Protocol)是互联网上应用最为广泛的一种网络协议。所有的WWW文件都必须遵守这个标准。设计HTTP
    最初的目的是为了提供一种发布和接收HTML页面的方法。1960年美国人Ted Nelson构思了一种通过计算机处理文本信息的方法，并称之为超文本
    （hypertext）,这成为了HTTP超文本传输协议标准架构的发展根基。Ted Nelson组织协调万维网协会（World Wide Web Consortium）和互联网工
    程工作小组（InternetEngineering Task Force ）共同合作研究，最终发布了一系列的RFC，其中著名的RFC 2616定义了HTTP 1.1。
    
##### http头字段

*general*

| *字段名* | *字段值* |  *含义*  |
| :-----: | :-----: | :-----: |
| Request URL | 字符串 | 要请求的url地址 |
| Request METHOD | get/post | 请求方式  |
| Status Code | 200,300,400,500 | 状态码: 200 请求成功 ; 300 资源重定向 ; 400 权限禁止 页面未找到等 ; 500 服务器错误 |
| Remote Address |  |  服务器IP地址 |
| Referrer Policy |  |   |


*request*
| *字段名* | *字段值* |  *含义*  |
| :-----: | :-----: | :-----: |
| Accept | 字符串 | 要请求的url地址 |
| Accept-Encoding |  | 请求方式  |
| Accept-Language |  | 状态码: 200 请求成功 ; 300 资源重定向 ; 400 权限禁止 页面未找到等 ; 500 服务器错误 |
| Cache-Control |  |  服务器IP地址 |
| Connection |  |   |
| Cookie |  |   |
| Host |  |   |
| Pragma |  |   |
| Referer |  |   |
| Upgrade-Insecure-Requests |  |   |
| User-Agent |  |   |

```http
Request URL:http://www.digpage.com/preface.html
Request Method:GET
Status Code:200 OK
Remote Address:103.218.240.147:80
Referrer Policy:no-referrer-when-downgrade

Response Headers

Access-Control-Allow-Origin:*
Cache-Control:max-age=600
Content-Encoding:gzip
Content-Type:text/html; charset=utf-8
Date:Sun, 23 Jul 2017 03:06:57 GMT
Last-Modified:Fri, 02 Dec 2016 15:33:50 GMT
Server:Coding Pages
Transfer-Encoding:chunked
Vary:Accept-Encoding

Request Headers

Accept:text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8
Accept-Encoding:gzip, deflate
Accept-Language:zh-CN,zh;q=0.8,en;q=0.6,zh-TW;q=0.4
Cache-Control:no-cache
Connection:keep-alive
Cookie:bdshare_firstime=1488159431860; Hm_lvt_4431b535ae6ac4132075a80a82007e46=1500020915,1500687130,1500773411; Hm_lpvt_4431b535ae6ac4132075a80a82007e46=1500773940
Host:www.digpage.com
Pragma:no-cache
Referer:http://www.digpage.com/web_request.html
Upgrade-Insecure-Requests:1
User-Agent:Mozilla/5.0 (Macintosh; Intel Mac OS X 10_12_4) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/59.0.3071.115 Safari/537.36
```

