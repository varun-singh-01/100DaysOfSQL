# SELECT Queries


| Syntax      | Description |
| ----------- | ----------- |
| select * from employees where first_name='Denis'; | Description of Query |
| select * from employees where first_name='Elvis' and gender='F'; | Description of Query |
| select * from employees where first_name='Kellie' and gender='F'; | Description of Query |
| select * from employees where first_name='Kellie' and gender in ('F', 'M'); | Description of Query |
| select * from employees where first_name like ('Mar%'); | Description of Query |
| select * from employees where first_name like ('Ma%r'); | Description of Query |
| select * from employees where first_name like ('Mar_'); | Description of Query |
| select * from employees where first_name not like ('mar_'); | Description of Query |
| select * from employees where first_name like ('mark%'); | Description of Query |
| select * from employees where hire_date like ('2000%'); | Description of Query |
| select * from employees where YEAR(hire_date) ='2000%'; | Description of Query |
| select * from employees where emp_no like ('1000_'); | Description of Query |
| select * from employees where hire_date between '1999-12-01' and '2000-01-01' order by hire_date; | Description of Query |
| select * from salaries where salary between '66000' and '70000' order by salary desc; | Description of Query |
| select * from departments where dept_no is not null; | Description of Query |
| select * from employees where first_name='Denis' and first_name='Elvis'; | Description of Query |
