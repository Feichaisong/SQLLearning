#SQL学习笔记
##SQL基础命令之DML
###SELECT查询语句
usage:SELECT "col_name" FROM "table_name" [WHERE "condition"];  
ex:SELECT E_NAME,E_NUM FROM EMP WHERE E_NUM BETWEEN 100 AND 999;
###INSERT INTO插入语句
usage:INSERT INTO "table_name" VALUES("col_name1","col_name2",...);
ex:INSERT INTO EMP VALUES("E_NUM","E_NAME",...);
###UPDATE SET更新语句
usage:UPDATE "table_name" SET "col_name1"="value1","col_name"="value2" WHERE "condition";
ex:UPDATE EMP A SET A.E_NAME="JISON" WHERE A.E_NUM=222;
###DELETE FROM 删除语句
usage:DELETE FROM "table_name" WHERE "condition";
ex:DELETE FROM EMP A WHERE A.E_NUM=234;
