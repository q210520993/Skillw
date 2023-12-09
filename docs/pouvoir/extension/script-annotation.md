---
title: 脚本注解
<<<<<<< HEAD
=======
id: 脚本注解
sidebar_position: 4
>>>>>>> 604cefa8 (迁移)
---
需要用到 [`ScriptAnnotationData`](https://doc.skillw.com/pouvoir/com/skillw/pouvoir/api/script/annotation/ScriptAnnotationData.html)

```kotlin
object : ScriptAnnotation(key) {
    override fun handle(data: ScriptAnnotationData) {
        //code
    }
}.register()
```

或

```javascript
//@Annotation
function exampleAnnotation(data) {
  //code
}
```
