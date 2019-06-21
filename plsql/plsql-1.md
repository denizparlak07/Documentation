# PL/SQL - 1

Hi, PL/SQL is a important topic for Oracle DBA or Oracle Developers. I will explain very basicly in this tutorial and

we would practice pl/sql code example.

So let's start

## PL/SQL Architecture

PL/SQL an do things that SQL cannot do in sql code

![alt text](https://github.com/denizparlak07/Documentation/blob/master/images/lnpls004.gif)

PL/SQL can do ;

Can run code bloks and it made of different bloks
Can debug Exception Handling
Only use Oracle Databsase
It allows 


### PL/SQL Block Architecture

It is a main structure of PL/SQL It runs DECLARE-BEGIN-END 

![alt text](https://github.com/denizparlak07/Documentation/blob/master/images/oracle-sqlplsql-context-switching-5-638.jpg)

Let's try example 

```sql
DECLARE

v_say NUMBER;
v_write VARCHAR2(20);

BEGIN

v_say:=1;
v_write:='PL/SQL Documentation';
DBMS_OUTPUT.PUT_LINE(v_write|| ' '||v_say);
END;
/

```

![alt text](https://github.com/denizparlak07/Documentation/blob/master/images/Screenshot_4.png)

Peace..
