
# モデルER図
 ```plantuml
class Users {
  * id:integer
  * name:string
  * email:string
}
class Miscroposts {
  * id:integer
  * content:text
  --
  * user_id:integer
}
Users ||-o{ Miscroposts
 ```