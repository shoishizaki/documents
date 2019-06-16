# うまく使えば便利だが、下手に使うとprojectを壊してしまうので気をつけよう！！

# New Project の作成
方法  
①githubを開く  
②Repositries→New→URLコピー  
③tower→左下の＋→clone Git Repository  
④ターミナル→作ったProjectの場所に移動→開く  
⑤Projectの作成  

# 変更後にすること  
tower→comit→push  

# Projectの開き方  
①ターミナルを開く  
②自分の開きたいProjectに移動する  
③開きたいエディタ＋スペース＋.  
 ex)atomで開く場合  
 　atom .  

# レビューの流れ
tower  
①Create New Branch from master  
②HEADを移す  
③変更する→commitする→pushする  
github  
④Compare & pull request  
⑤Reviewersを設定する→commentを入れる  
⑥Create pull requests  
⑦レビューをみる  
　if 修正が必要なら  
　　　修正→commit→pushの流れ  
　elif OKなら  
　　　　Merge pull request→Towerでpullする  
＊使い終わったbranchは削除する   

# githubでリポジトリの作成を行いlocalにcloneを行うとき
①リモートリポジトリにあるclone or downloadボタンを押し、リモートリポジトリurlをコピーする。  
②ターミナルからローカルリポジトリを設置したいディレクトリに移動して、コマンドでリモートレポジトリをクローンする。  →git clone git@github.com:<account name>/class-material-github.git  

# 既存のファイルをgitにあげるとき  
①git init : gitの初期設定をする。 .gitのファイルが作成される。  
②git add : gitに追加。　localにあるものをgit localに上げる。  
③git commit -m "コメント" : gitに確定する。gitのサーバーに上げる準備をする。  
④git remote add origin _________ : _________に紐ずける。  
  tower
  add repositoryでtower上にrepositoryを作成する

# githubのforkとは
  Creating a “fork” is producing a personal copy of someone else’s project. Forks act as a sort of bridge between the original repository and your personal copy. You can submit Pull Requests to help make other people’s projects better by offering your changes up to the original project.
