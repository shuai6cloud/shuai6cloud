# 期末作业
18信管袁帅 201804213001

一、准备工作

进行git的安装，并在阿里云和github上注册账号

安装vscode，sqlite3（sqlite3,sqlite3.dll,sqlite3.def）

如图，进行git，sqlite3，python的环境变量配置，在path处加入git-core，sqlite和python的scripts

配置完毕后检验能否运行

进行账户（global-user）的设置

进行公钥的设置，同时将公钥添加到github的ssh-key处

二、开始操作

创建repos文件夹，在里面添加shuai6cloud文件夹

用django-admin startproject mysite建立mysite文件夹及其附带文件

用python manage.py startapp polls和python manage.py startapp news2创建这两个项目

利用sqlite3进行包含文件的查看：

sqlite3——.open db.sqlite3——.tables

用.quit退出查看

输入：python manage.py migrate

python manage.py makemigrations

三、进行第一个网站的编辑

利用git clone git@github.com:fwqcuc/Django_Example.git这一串代码在本地文件夹中拷贝老师的Django_Example

对照老师的文件中的每一部分，对于自己的news2中的文件代码进行修改：

对于admin.py  model.py views.py 进行修改

创建templates文件夹及其子文件base.html,year_archive.html 并对于文件位置进行调整，然后按照老师的例子进行代码修改

创建urls.py 文件，并按照示例进行编辑

编辑完毕，进行保存，然后进行上传：

git add .

git commit -m ""

git push

输入python manage.py runserver

在浏览器输入http://localhost:8000/news2/articles/2020/

结果如下图所示

在vscode中按ctrl+c退出

四、进行第二个网站的编辑

在第一个作业的基础上添加homework_form.html文件，并根据老师提供的代码进行该文件的编辑以及其他文件的修改

add-commit-push 三步,上传github

输入http://localhost:8000/news2/hw/create/

结果如下图所示

注：在操作过程中由于电脑和设置的问题还出现了一些错误，但是在上网搜索和向老师提问后都得到解决，因此在实验报告上没有体现。







