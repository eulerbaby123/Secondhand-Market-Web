md
# Second-Market
校园二手交易平台 | Campus Second-Hand Market

基于 **Python + Django + MySQL** 开发的轻量化校园二手交易系统，支持商品发布、购买、搜索、管理等完整交易流程，界面简洁、功能完善，适合课程设计、毕业设计、二次开发。

---

## ✨ 技术栈
- **后端**：Python 3.x + Django 3.2.11
- **数据库**：MySQL 5.7 / 8.0
- **前端**：HTML5 + CSS3 + JavaScript
- **图片处理**：Pillow

---

## 📦 依赖清单
```txt
asgiref==3.8.1
Django==3.2.11
mysqlclient==2.2.4
Pillow==9.1.1
pytz==2024.1
sqlparse==0.5.0
typing_extensions==4.12.2
一键安装依赖：
bash
运行
pip install -r requirements.txt
🚀 运行步骤
创建 MySQL 数据库数据库名：cucmarket
导入数据库结构执行项目中的 cucmarket.sql 文件，初始化数据表
配置数据库连接修改 settings.py 中的 MySQL 账号和密码：
python
运行
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'cucmarket',
        'USER': '你的用户名',
        'PASSWORD': '你的密码',
        'HOST': '127.0.0.1',
        'PORT': '3306',
    }
}
启动项目
bash
运行
python manage.py runserver
访问系统浏览器打开：
plaintext
http://127.0.0.1:8000/
👤 测试账号
普通用户
可自行注册
管理员账户
用户名：1033220521
密码：1234qwer@
管理员后台：
plaintext
http://127.0.0.1:8000/admin/
📌 项目说明
本项目为校园二手交易市场完整源码，包含：
用户注册 / 登录
商品发布、编辑、删除
商品分类、搜索、浏览
订单管理
后台管理系统
适合课程设计、毕业设计学习与二次开发。
