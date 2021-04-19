## curl 参数

不带有任何参数时，curl 就是发出 GET 请求。


-I参数向服务器发出 HEAD 请求，然会将服务器返回的 HTTP 标头打印出来
$ curl -I https://www.example.co

参数将服务器的回应保存成文件，等同于wget命令。
$ curl -o example.html https://www.example.com

shell curl 取得HTTP返回的状态码
curl -I -m 10 -o /dev/null -s -w %{http_code} www.baidu.com
