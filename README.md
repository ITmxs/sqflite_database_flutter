# Flutter Tutorial - Database Storage Using Sqlite & Sqflite
在此之前相信大家都使用过shared_preferences

插件地址：https://pub.flutter-io.cn/packages/shared_preferences

今天给大家介绍的是sqflite

插件地址：https://pub.flutter-io.cn/packages/sqflite

目前他支持支持 iOS、Android 和 MacOS，遗憾的flutter web不受支持，不过后面应该会去支持



```yml
 sqflite:
```



目前：

- 支持事务和批量
- 打开期间的自动版本管理
- 插入/查询/更新/删除查询的助手，就和go语言的gorm一样，很便捷
- 在 iOS 和 Android 上的后台线程中执行的 DB 操作

为什么使用数据库，存储大量数据是比较方便的，如果少的话，完全可以使用我上面提过的这个



使用它的四个步骤

1.引入

2.打开数据库

3.创建数据库

4.执行CRUD相关操作

开始

