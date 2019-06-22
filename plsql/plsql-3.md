# PL/SQL - Data type & Variables

We are continue PL/SQL Tutorial. Today, we gonna look the Data type and variables. This is realy boring topic

because there are too much variables and Data types that means too much theoric information.

But don't worry i just share only image and gif that issue and i don't write too much. 

I share some pdf that include Data type, you can use anytime and now let's make a practice



```sql
DECLARE

vtest1 VARCHAR2(10):='Oracle';
vtest2 CHAR(10):='Oracle';

BEGIN

IF vtest1=vtest2 THEN
DBMS_OUTPUT.PUT_LINE(vtest1|| " and "||vtest2||' are same ');
ELSE
DBMS_OUTPUT.PUT_LINE(vtest1|| " and "||vtest2||' are different ');
END IF;
END;
/
```

![alt text](https://github.com/denizparlak07/Documentation/blob/master/images/Screenshot_12.png)

### Find the old date using to_char

```sql
SELECT HR.EMPLOYEE_ID,FIRST_NAME || ' ' || LAST_NAME, TO_CHAR(HIRE_DATE,'DD,MM,YYYY') FROM HR.EMPLOYEES 

WHERE FIRST_NAME LIKE 'S%';
```



![alt text](https://github.com/denizparlak07/Documentation/blob/master/images/to_char_gif.gif)

Peace..
