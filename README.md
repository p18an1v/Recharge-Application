# Recharge-Application
A recharge application using JSP, Servlet and SQL
Create appropriate tables in SQL from the db package db_operations
Change the username and password in DbConnection class
Used apache tomcat 9 as the server


Bank2 sql tables - bank_account CREATE TABLE bank_account ( CUST_NAME VARCHAR2(20), USR_NAME VARCHAR2(20), ACC_NO NUMBER(10) NOT NULL PRIMARY KEY, PASSWORD VARCHAR2(20), PHONE_NO NUMBER(11), ACC_BAL FLOAT(126) );

bank_recharge CREATE TABLE bank_recharge ( ACC_NO NUMBER(10), PHONENO VARCHAR2(20), ISP VARCHAR2(20), REC_AMT FLOAT(126), REC_DATE VARCHAR2(20), PRIMARY KEY (ACC_NO, REC_DATE) );
