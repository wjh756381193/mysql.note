修改字符集
```
alter table posts convert to character set utf8 collate utf8_general_ci;
```

查看建表语句
```
show create table `table_name`;
```

创建数据库
```
create database a;
create database [ if not exists ] b;
```

显示建库语句
```
show create database a;
```

删除db
```
drop database [ if exists ] a;
```

删除table
```
drop table if exists `tbname`
```

创建index/删除index
```
create index index_name on table_name (field_name);

drop index index_name on table_name;
```


