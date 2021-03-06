# MINISQL

---

一个精简型单用户SQL引擎(DBMS)MiniSQL

**实验平台**：Visual Studio 2017

**实验内容**：精简型DBMS

**实现功能**：

1. 总功能：允许用户通过字符界面输入SQL语句实现表的建立/删除；索引的建立/删除以及表记录的插入/删除/查找； 
2. 数据类型：支持三种基本数据类型：INT，CHAR(N)，FLOAT，其中CHAR(N)满足 1 <= N <= 255； 
3. 表定义：一个表最多可以定义32个属性，各属性可以指定是否为UNIQUE；支持单属性的主键定义； 
4. 索引的建立和删除：对于表的主属性自动建立B+树索引，对于声明为UNIQUE的属性可以通过SQL语句由用户指定建立/删除B+树索引（因此，所有的B+树索引都是单属性单值的）； 
5. 查找记录：可以通过指定用AND连接的多个条件进行查询，支持等值查询和区间查询； 
6. 插入和删除记录：支持每次一条记录的插入操作；支持每次一条或多条记录的删除操作。
