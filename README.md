运行方法：

下载代码到本地

```
git clone https://github.com/teddyxiong53/flaskr
```

创建一个virtualenv并激活

```
cd flaskr
virtualenv venv
source venv/bin/activate
pip install flask
```

初始化数据库

```
# 退出到flaskr目录的上一层
cd ..
export FLASK_APP=flaskr
export FLASK_ENV=development
flask init-db
```

运行：

```
flask run -h 0.0.0.0
```

然后访问ip:5000即可。

