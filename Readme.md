### pl-sql

***
Sample function to update salaries

```
create or replace function
new_salary(current_salary number,depatment_id number)
return number is
working_salary number;
begin
working_salary := current_salary * 1.2;
if department_id = 101 then
working_salary := working_salary * 1.05;
end if;
return workinig_salary;
end;
/

```
