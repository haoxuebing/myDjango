# Django
### 基于Python的高级web开发框架，高效快速开发，高度集成，开源免费

### pip install Django==2.1.1  #安装
### python -m django --version  #检测版本
### django-admin startproject  mydemo  #创建django项目
### python manage.py runserver 9999

### python manage.py startapp blog #创建blog模块
### 把blog模块添加到settings.py 的 INSTALLED_APPS 模块

### urls.py  路由配置文件

### SQLite Expert Personal #免费轻量的SQLite客户端

## 生成数据表
### python manage.py makemigrations  app名（可选）  #不写默认所有
### python manage.py  migrate  #执行迁移
### Django 会自动在 app/migrations/ 目录下生成移植文件
### python manage.py sqlmigrate 应用名 文件id  #查看SQL语句
### python manage.py sqlmigrate blog 0001
### 默认sqlite3的数据库在项目根目录下 db,sqlite3

## Admin
### python manage.py createsuperuser  创建超级用户

## 改变语言
### setting.py LANGUAGE_CODE='zh_Hans'   #en_us 英文
