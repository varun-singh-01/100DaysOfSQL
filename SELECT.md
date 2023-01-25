# SELECT Queries


select * from employees where first_name='Denis';
select * from employees where first_name='Elvis' and gender='F';
select * from employees where first_name='Kellie' and gender='F';
select * from employees where first_name='Kellie' and gender in ('F', 'M');
select * from employees where first_name like ('Mar%');
select * from employees where first_name like ('Ma%r');
select * from employees where first_name like ('Mar_');
select * from employees where first_name not like ('mar_');
select * from employees where first_name like ('mark%');
select * from employees where hire_date like ('2000%');
select * from employees where YEAR(hire_date) ='2000%';
select * from employees where emp_no like ('1000_');
select * from employees where hire_date between '1999-12-01' and '2000-01-01' order by hire_date;
select * from salaries where salary between '66000' and '70000' order by salary desc;
select * from departments where dept_no is not null;
select * from employees where first_name='Denis' and first_name='Elvis';

