## userページ

|メソッド  |url  |アクション  |内容  |
|---------|-----|----------|-----|
|Get |/users  |index  |すべてのユーザーを一覧するページ  |
|Get  |/users/1  |show  |id=1のユーザーを表示するページ  |
|Get |/users/new  |new  |新規ユーザーを作成するページ  |
|Get |/users  |create  |ユーザーを作成するアクション  |
|Get |/users/1/edit/  |edit  |id=1のユーザーを編集するページ  |
|Patch |/users/1  |update  |id=1のユーザーを更新するアクション  |
|Delete |/users/1  |destroy  |id=1のユーザーを削除するアクション  |

## micropostページ
|メソッド  |url  |アクション  |内容  |
|---------|-----|----------|-----|
|Get |/microposts  |index  |すべてのマイクロポストを表示するページ  |
|GET  |/microposts/1  |show  |id=1のマイクロポストを表示するページ  |
|Get |/microposts/new  |new  |マイクロポストを新規作成するページ  |
|Post |/microposts  |create  |マイクロポストを新規作成するアクション  |
|Get |/microposts/1/edit/  |edit  |id=1のマイクロポストを編集するページ  |
|Patch |/microposts/1  |update  |id=1のマイクロポストを更新するアクション  |
|Delete |/microposts/1  |destroy  |id=1のマイクロポストを削除するアクション  |