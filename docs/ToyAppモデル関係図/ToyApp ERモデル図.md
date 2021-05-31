# モデル ER 図

```plantuml
package "ER図" as er {
class Users {
 * id:[int]
 * name:[str]
 * email:[str]
}
class Miscroposts {
 * id:[int]
 * content:text
 --
 * user_id:[int]
}
}
Users ||-o{ Miscroposts

```
