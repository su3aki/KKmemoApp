# ページ設計書(users_index)
## 概要
| URL             | アクション | HTTP メソッド | 用途                                   |
| --------------- | ---------- | ------------- | -------------------------------------- |
| /users          | index      | GET           | すべてのユーザーを一覧表示するページ       |
## 構成

- **Users(title)**

- **ユーザーリスト(table)**
name(th)  
e-mail(th)  
user_name(td)  
user_e-mail(td)  
Show(botton)  
Edit(botton)  
Destroy(botton)  
Are you sure?(削除確認ポップアップ)  

- **New User(botton)**

## 機能
- ユーザーリストを表示
- 各ユーザーごとのshow,editへ遷移するボタン
- ユーザーを削除するボタン
- ユーザー新規作成へ遷移するボタン

## 関連アクション
- index
index画面をレンダリング
- show
特定ユーザー表示画面をレンダリング
- edit
特定ユーザー編集画面をレンダリング
- destroy
特定ユーザーをdeleteする
- new
ユーザー新規作成画面をレンダリング