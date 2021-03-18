# MkDocsのセットアップ

## 1.Githubからclone
[ここから](https://github.com/kentotoda/MkDocs)ソースをcloneしてきます
```
git clone https://github.com/kentotoda/MkDocs.git
```

## 2.環境作成
```
pipenv install
```
で環境作成ができます

## 3.ビルド
```
pipenv shell
```
コマンドで作成した環境に入り、
```
mkdocs build
```
でmkdocsの中身をビルドします

## 4.画面で確認
```
mkdocs serve
```
でサーバを起動し  
[http://localhost:8000](http://localhost:8000)
にアクセスすると作成した画面が確認できます！