# Django3.0搭建简单的记事本应用

基于python3.7.2 Django 3.0.8框架

## 

1. 可以先输入以下命令创建一个登入admin的账户

   ```
   python manage.py createsuperuser
   ```

2. 创建一个模型（若不是从头开始跳过本步骤）

   ```
   python manage.py startapp tasks
   ```

3. 在你改动了 models.py 的内容之后执行下面的命令

   ```
   python manage.py makemigrations
   ```

   相当于在该app下建立 migrations目录，并记录下你所有的关于models.py的改动

4. 在 makemigrations之后执行命令

   ```
   python manager.py migrate
   ```

   将该改动作用到数据库文件，比如产生table，修改字段的类型等

5. 运行项目

   ```
   python manager.py runserver
   ```

   

## v1.0

1. 具有增、删、改和删除线等功能
2. 实现了前端css的美化

## v1.1

1.实现删除与修改按钮的diolog弹出样式

