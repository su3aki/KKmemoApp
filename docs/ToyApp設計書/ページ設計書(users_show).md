# users/show.html 　基本設計書

---

## URL とアクション

| URL           | アクション | http メソッド |
| ------------- | ---------- | ------------- |
| /users/:id    | show       | GET           |

## ページ内の要素

- 対象 id の user_name
- 対象 id の user_email
- ボタン : back
- ボタン : edit

## ページ要素の機能

#### ボタン:back

    Link to /users

#### ボタン:edit

    Link to /users/:id/edit
    
  
## 関連するアクション

#### showアクション
関連するuser_idのuser_nameとuser_emailをデータベースへGETリクエストしレンダリングする

#### updateアクション(/users/edit からの httpリクエスト)
/users/:id/edit における**Update User ボタン**から対象 id の/users/:id へ**PATCH**メソッドが走る
