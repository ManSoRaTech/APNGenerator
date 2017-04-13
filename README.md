ManSora APN Generator
===================
iOS APN 描述文件生成器

a flask fork of [APNManager](https://github.com/realityone/APNManager)

使用：
    
    pip install -r requirements.txt
    python app.py

然后浏览器访问  ：http://127.0.0.1:5000/  
Squid Proxy 访问：http://127.0.0.1:5000/squid/  

如果需要更改监听IP以及端口,请修改app.py里的以下行

    app.run(host="127.0.0.1",port=5000)

APN 搭建教程见[iOS-APN-across-the-great-fire-wall](http://lazymind.me/2016/01/iOS-APN-across-the-great-fire-wall/)


