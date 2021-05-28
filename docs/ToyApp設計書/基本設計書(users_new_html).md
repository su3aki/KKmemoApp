 # users/new.html　基本設計書
 ---
## -URLとアクション

 |  URL  |  アクション  |
 | ---- | ---- |
 |  /users/new |  new |

## -ページ内の要素
 - タイトル : New user
 - フォーム 
    param: name , email
    button: create user
 - ボタン : back

## -ページ要素の機能
 - フォーム
    User.name 
    User.emailを指定して、create action にPostする
 - ボタン:back
    
## 関連するアクション
  - new
    user作成画面をレンダリング
  - create
    new.htmlからpostされたパラメータをバリデーションしてDBに保存


