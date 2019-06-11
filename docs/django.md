# プロジェクトとは  
　あるウェブサイト向けに設定ととアプリケーションを集めたもの    

# アプリケーションとは
　実際に何らかの処理を行うウェブアプリケーション  

# Djangoとは
 ・pythonで記述したアプリケーションを作るときにアプリケーション開発に必要な部品を準備してくれているもの。  

# MTVモデル  
 MTVとは  
 ・Model(データベースに格納されているデータ)  
 ・Template(テンプレートファイルによって定義されたそれぞれのページのデザイン)  
 ・View(どのページを表示させるかを決定する処理):いわゆるコントローラー  

# プロジェクト内ファイル
## __init__.py
  This is a blank Python script that due to its special name let’s Python know that this directory can be treated as a package    

## settings.py
  This is where you will store all your project settings  

## urls.py
  This is a Python script that will store all the URL patterns for your project. Basically the different pages of your web application.  

## wsgi.py
  This is a Python script that acts as the Web Server Gateway Interface. It will later on help us deploy our web app to production  

## manage.py
  This is a Python script that we will use a lot. It will be associates with many commands as we build our web app!  

# アプリ内ファイル
## __init__.py
  This is a blank Python script that due to its special name let’s Python know that this directory can be treated as a package  

## admin.py
  You can register your models here which Django will then use them with Django’s admin interface.  

## apps.py
  Here you can place application specific configurations  

## models.py
  Here you store the application’s data models  

## tests.py
Here you can store test functions to test your code  

## views.py
  This is where you have functions that handle requests and return responses  

## Migrations folder
  This directory stores database specific information as it relates to the models  

# モデルの変更を行うための３ステップガイド
・モデルを変更する（models.pyの中の）  
・これらの変更のためのマイグレーションを作成するために python manage.py makemigrations を実行します。  
・データベースにこれらの変更を適用するために python manage.py migrate を実行します。  

# render()
render(request, template_name, context=None, content_type=None, status=None, using=None)  
Combines a given template with a given context dictionary and returns an HttpResponse object with that rendered text.  
##Required arguments¶
request  
The request object used to generate this response.  
template_name  
The full name of a template to use or sequence of template names. If a sequence is given, the first template that exists will be used.   
