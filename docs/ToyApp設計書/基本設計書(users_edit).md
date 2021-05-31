# ページ設計書(users_edit)
## 概要
| URL             | アクション | HTTP メソッド | 用途                                   |
| --------------- | ---------- | ------------- | -------------------------------------- |
| /users/:id/edit          | edit      | GET           | id=1のユーザーを編集するページ       |
## 構成

- **Users(title)**

- **ユーザーリスト(table)**
name(th)  
e-mail(th)  
user_name(td)  
user_e-mail(td)  
Submit(botton)  
Show(botton)  
Index(botton)  

- **New User(botton)**

## 機能
- ユーザー編集フォームを表示
- 各ユーザーごとのshow,indexへ遷移するボタン
- updateアクションにpostするボタン

## 関連アクション
- index
index画面をレンダリング
- show
特定ユーザー表示画面をレンダリング
- edit
特定ユーザー編集画面をレンダリング
- update
特定ユーザーをupdateする