OLTP---Oracle, MySQL, SQL server. RDBMS(relationship of database management system) is the typical OLTP application.  
OLAP---extract, transform, and load data from OLTP  
<br>
<br>
<br>

DW(Datawarehouse) got four attributes--subject-oriented, integrated, Non-Volatile, and Time-Variant.  
there is not much deletion and modification in DW.  
<br>
<br>
<br>
Structure data and unstructure data
<br>
<br>
<br>
DDL(data definition language) and DML(data manipulation language)  
DDL---creat database, creat tables  
DML---select, update, insert, and delete....   
<br>
<br>
Hive is to map a data file into a table.--- check sql syntaxcompile, sql language, and explain matadata.  

<img src="https://user-images.githubusercontent.com/111692657/210121683-c43fef1d-e34b-4f76-8ae4-162751fd1708.png" width="500">  
there are three user interface in Hive---CLI(command line interface), JDBC(API)(java database connectivity), ODBC(open database connectivity), and WebGUI  
<br/>
<br/>
matadata in Hive is the mapping between data file and table---.txt to .csv or .xls  
<br>
<br>
there are five drivers in Hive---parser(complier), planner, execution, optimizer, and MS clents.  
also, there are different engine provided for Hive to process data like mapreduce, tez, and sparks.  
Matastore is kind of like matadata manager---control permission, 
<img src="https://user-images.githubusercontent.com/111692657/210122007-1b90f1a2-9d03-4f21-97d6-735a6cf39954.png" width="500">  
<br>
<br>
<img src="https://user-images.githubusercontent.com/111692657/210122097-76ae60b6-c241-46f9-823a-858d48c23017.png" width="500">  
<br>
<br>
<img src="https://user-images.githubusercontent.com/111692657/210122060-1d8619f9-f37e-44bc-98c0-5b2c4b78795a.png" width="500">
<br>
<br>
activiate matastore---nohup -path --service matastore & and logs were stored in /root/nohup.log  
besides, there are two clents in Hive, beeline(new) and Hive(old)  
<img src="https://user-images.githubusercontent.com/111692657/210122622-08b51e36-049f-4d44-abcc-0d3b67d32875.png" width="500">  
<br/>
<br/>
if we want to use beeline, we have to activate matastore first and then start hiveserver2.  
beeline connect command:! connect jdbc:hive2://node1:10000  we have to know where hiveserver2 is and what port we use.  
<br>
<br>
DDL commands---create, drop, alter, use.

-------------------------------------------------------------------------------------
Functions in Hive
two types of functions in Hive----build in functions and UDF(user defined function)
also, there are three types of UDF---UDF, UDAF(user defined aggregation function), and UDTF(user defined table generating function)











