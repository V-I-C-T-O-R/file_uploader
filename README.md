### 修复此项目多文件上传覆盖问题，优化用户体验

##### flask+webuploader实现多文件上传demo

运行步骤：
```
1. git clone https://github.com/abbeyokgo/flask_multi_uploader.git
2. cd flask_multi_uploader
3. pip install -r requirements.txt
4. gunicorn -k eventlet -b 0:8888 server:app
```
然后即可访问：127.0.0.1:8888

![](http://wx2.sinaimg.cn/large/0060lm7Tly1fw5m7ppzh4g30wo0ko7wh.gif)
