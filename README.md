# ***book_store***
## 初始配置
创建项目环境
```bash
$ virtualenv env
$ . ./env/bin/activate # 激活环境
(env) $
```
安装安装相关依赖包
```bash
(env) $ pip install -r requirements.txt
```
建立数据库表
```bash
$ python manage.py migrate
$ python manage.py runserver
```
启动服务端
```bash
$ python manage.py runserver
```