#### 1. 笔记表(note)

| 字段名   | 数据类型      | 默认值     | 允许非空 | 索引自增           | 备注     |
| -------- | ------------- | ---------- | -------- | ------------------ | -------- |
| nid      | int(16)       |            | NO       | PRI auto_increment | 笔记编号 |
| title    | varchar(50)   |            | YES      |                    |          |
| content  | varchar(4096) |            | YES      |                    |          |
| pub_time | varchar(10)   | xxxx-xx-xx | YES      |                    |          |

#### 2. 收藏表(collect)

| 字段名 | 数据类型     | 默认值 | 允许非空 | 索引自增           | 备注         |
| ------ | ------------ | ------ | -------- | ------------------ | ------------ |
| cid    | int(16)      |        | NO       | PRI auto_increment | 编号         |
| title  | varchar(64)  |        | YES      |                    |              |
| url    | varchar(128) |        | YES      |                    |              |
| intr   | varchar(256) |        | YES      |                    | 收藏内容简介 |

#### 3. 随笔表(jotting)

| 字段名   | 数据类型      | 默认值     | 允许非空 | 索引自增           | 备注 |
| -------- | ------------- | ---------- | -------- | ------------------ | ---- |
| jid      | int(16)       |            | NO       | PRI auto_increment | 编号 |
| title    | varchar(50)   |            | YES      |                    |      |
| content  | varchar(4096) |            | YES      |                    |      |
| pub_time | varchar(10)   | xxxx-xx-xx | YES      |                    |      |

#### 4. 心情(mood)

| 字段名  | 数据类型    | 默认值 | 允许非空 | 索引自增           | 备注 |
| ------- | ----------- | ------ | -------- | ------------------ | ---- |
| mid     | int(16)     |        | NO       | PRI auto_increment | 编号 |
| content | varchar(32) |        | NO       |                    | 内容 |
| date    | varchar(10) |        | NO       |                    | 时间 |