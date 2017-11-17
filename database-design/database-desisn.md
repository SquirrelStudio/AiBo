This is database-design.md file 


### 博文表

|字段名称  | 字段类型 |
|:--------:|:--------:|
|编号bid   | varchar  |
|种类      |varchar   |
|分类      |int       |
|子分类    |int       |
|标题      |varchar   |
|摘要      |varchar   |
|内容      |varchar   |
|发布时间  |date      |
|编辑时间(最后一次编辑时间) |date|
|作者      |int       | 

### 用户表

|字段名称   |   字段类型|
|:---------:|:--------:|
|用户编号uid|  int     |
|用户昵称   |  varchar |
|用户真实姓名| varchar |
|用户性别    | varchar |
|用户出生年月| date    |
|用户籍贯    | varchar |
|用户所在地  | varchar |


### 密码表
|字段名称 |字段类型|
|:-------:|:------:|
|用户编号uid| int  |
|密码       |varchar(加密后的密码) |
|密码编辑时间(上次修改时间)| date |

### 热门博文

|字段名称|字段类型|
|:------:|:------:|
|博文pid |varchar |
|博主uid |int     |

### 热门评论

|字段名称|字段类型|
|:------:|:------:|
|评论cid |int     |

