# 表

在 eKuiper 中，表是源数据在当前时间的快照。相比于普通的数据库表，eKuiper 中的表会随着时间而变化。

表的数据源既可以是无界的也可以是有界的。对于有界数据源来说，其表的内容为静态的。若表的数据源为无界数据流，则其内容会动态变化。

## 表内容更新

当前，表的内容更新仅支持追加。用户创建表时，可以指定参数限制表的大小，防止占用过多内存。

## 表的使用

表不能在规则中单独使用，必须与流搭配，通常用于与流进行连接。表可用于补全流数据或作为计算的开关。

## 更多信息

- [表用法](../../sqls/tables.md)