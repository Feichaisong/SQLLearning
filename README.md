#SQL学习笔记
##SQL基础命令之DML
###SELECT查询语句
USGE:SELECT "col_name" FROM "table_name" [WHERE "condition"];  
EX:SELECT E_NAME,E_NUM FROM EMP WHERE E_NUM BETWEEN 100 AND 999;
###INSERT INTO插入语句
USAGE:INSERT INTO "table_name" VALUES("col_name1","col_name2",...);  
EX:INSERT INTO EMP VALUES("E_NUM","E_NAME",...);
###UPDATE SET更新语句
USAGE:UPDATE "table_name" SET "col_name1"="value1","col_name"="value2" WHERE "condition";  
EX:UPDATE EMP A SET A.E_NAME="JISON" WHERE A.E_NUM=222;
###DELETE FROM 删除语句
USAGE:DELETE FROM "table_name" WHERE "condition";  
EX:DELETE FROM EMP A WHERE A.E_NUM=234;
##SQL之DDL
###CREATE 创建语句
USAGE:CREATE TABLE "table_name"("col_name1" datatype,"col_name" datatype,...)  
EX:CREATE TABLE SALES(E_NUM NUMBER,E_NAME VARCHAR2(20),E_SALES NUMBER);
###ALTER 更改表结构
USAGE:  
  1、ALTER TABLE "table_name" ADD "col_name" DATATYPE  
  2、ALTER TABLE "table_name" DROP "col_name"
###DROP 用于删除表、索引、数据库
