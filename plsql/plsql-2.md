We are continue PL/SQL Tutorial. Today, we gonna look the set value to variable.

We use the this rule **:=** when set value 

```sql
DECLARE

v_write VARCHAR2()20

BEGIN

v_write:='Oracle PL/SQL';
DBMS_OUTPUT.PUT_LINE(v_yaz);
END;
/
```
There has a lot of Characters on PL/SQL ,take a look at these

![alt text](https://github.com/denizparlak07/Documentation/blob/master/images/plsql_gif.gif)

Let's try,

```sql
DECLARE
   number_1   NUMBER;
   number_2   NUMBER;
BEGIN
   number_1 := 10;
   number_2 := 5;

   IF number_1 > number_2
   THEN
      DBMS_OUTPUT.PUT_LINE (number_1 || ' bigger than ' || number_2);
   ELSE IF number_2 > number_1
      THEN
         DBMS_OUTPUT.PUT_LINE (number_2 || 'bigger than ' || number_1);
      END IF;
     END IF;
   END;
/

```

![alt text](https://github.com/denizparlak07/Documentation/blob/master/images/Screenshot_5.png)

Peace..
