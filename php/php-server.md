### $_SERVER

##### server

| *字段名* | *含义* |
| :-----: | :-----: | 
| SERVER_NAME | 服务器名称 |  
| SERVER_ADDR | 服务器地址 |
| SERVER_SOFTWARE | 服务器软件 |  
| SERVER_PROTOCOL | 请求协议 如:HTTP/1.1 |
| SERVER_ADMIN  | 该值指明了 Apache 服务器配置文件中的 SERVER_ADMIN 参数。如果脚本运行在一个虚拟主机上，则该值是那个虚拟主机的值。 |  
| SERVER_POST | Web 服务器使用的端口 |
| SERVER_SIGNATURE | 包含了服务器版本和虚拟主机名的字符串 |
| REQUEST_METHOD | 请求方式 HEAD PUT GET POST DELETE |
| REQUEST_TIME | 请求开始的时间戳 |  
| REQUEST_TIME_FLOAT | 请求开始的时间戳 精确到微妙 |
| SCRIPT_FILENAME | 当前执行脚本的绝对路径 |
| SCRIPT_NAME | 包含当前脚本的路径。这在页面需要指向自己时非常有用。__FILE__ 常量包含当前脚本(例如包含文件)的完整路径和文件名 |
| REQUEST_URI | 要访问的url |
| PATH_INFO | 包含由客户端提供的、跟在真实脚本名称之后并且在查询语句（query string）之前的路径信息，如果存在的话 |
| QUERY_STRING | query string（查询字符串），如果有的话，通过它进行页面访问。 |
##### remote

| *字段名* | *含义* |
| :-----: | :-----: |
| REMOTE_HOST | 客户端主机名 |
| REMOTE_POST | 客户端用来发送http请求的端口 |
| REMOTE_ADDR | 客户端ip地址 |
