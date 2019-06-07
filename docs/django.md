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
