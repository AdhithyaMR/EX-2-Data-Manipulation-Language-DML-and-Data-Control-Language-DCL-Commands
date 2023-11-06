# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## DATE: 10/08/2023
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![270731124-b32bceb5-9f0f-4c30-b27f-c4375e677f46](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/c0035606-8e37-4791-b48e-2fd34d69f944)
### OUTPUT:
![270852396-db8ff768-f851-4ee1-98d4-b25fc97b52c2](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/0b902c3e-d7ae-42a5-b4fc-d06943094b37)

### Q2) Delete the records from manager table where the salary less than 2750.
### QUERY:
![270718856-15e1ebf0-899f-4589-aee8-0ea4570cefba](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/af5a5e05-23e5-4157-9310-a3a67b817a29)
### OUTPUT:
![270731685-ad0c2970-47bc-4591-8f4b-a295a38b092d](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/ca9586e9-ef9e-48fa-9ac0-0d53bef7e545)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![270733395-72faf04a-7d00-4070-8b1b-433f67d05a51](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/68d421b6-49c7-4e4c-b853-a63afd3f3927)


### OUTPUT:

![270733298-b697b096-ba16-4329-ac6b-d015128fd061](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/9dbe920d-eef1-4a71-a660-020a8382e00c)

### Q5)	List the names of Clerks from emp table.


### QUERY:

![270737656-b1f05e5a-a309-424e-b910-cb103f5413e3](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/59d03b94-48b5-4df8-be9a-5749d9839b84)

### OUTPUT:
![270738265-f8bc5ab3-f99d-400e-aa3f-c1f6c4a06c5d](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/beca32ac-9ddb-4df2-bffe-c5904e6cf4de)


### Q6)	List the names of employee who are not Managers.


### QUERY:
![270738366-01b12f80-95f7-431c-95a7-4470c12c4a72](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/589bc4e0-7695-4eb2-893a-cb4c1350b64a)


### OUTPUT:
![270738422-0cf2a6ad-398f-4d29-bebb-c31a84334347](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/f7acbce8-6e7d-4fbb-af52-5acc26b5f699)


### Q7)	List the names of employees not eligible for commission.


### QUERY:
![270738943-42336775-5693-4b45-93b4-f60e6b80183c](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/1a0327a7-6a62-47e9-86f2-9c738e5a4235)


### OUTPUT:
![270739010-8f6da561-78ad-4573-9c8b-406de97e5e19](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/f4a2b0d9-c8da-4323-bb08-15c0d965f8a2)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![270739894-63e34f73-6454-4c79-bafd-403fbb23ca66](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/335da4d7-018b-4ca1-a57a-cdb4b57b4418)


### OUTPUT:
![270739952-b947469e-7ad5-4b63-966b-652d7d2c8c0f](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/502437b0-2399-4579-a557-60594dd696cf)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:
![270742384-ea09fd51-d67f-4b14-abc7-7093026e69dd](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/3d3e6064-8b9c-4ade-912a-6338e4b38d41)


### OUTPUT:

![270742433-b3a0080f-b755-412a-b631-2c8484061c1c](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/93d86c37-76d3-477a-9869-f3c52938faf2)

### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![270743084-d96047cf-2bbb-4e35-9509-b6948cc69eff](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/5ee48983-aea1-40fd-afee-08b2953b25ec)


### OUTPUT:
![270743263-dc101670-2467-428c-bf52-734adc718334](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/9aa9b0a2-a783-430d-bd98-389edfd01a1b)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![270743688-b195dae7-d5fb-405b-b0fd-8f3cac28497c](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/69e2a111-09de-4bea-baeb-bb407cf7ef47)


### OUTPUT:

![270743781-8366de8d-6502-4a70-a202-8540b84db42c](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/f9599776-6835-4d4f-a55a-57e4c876176e)

### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![270744159-ab24e141-c401-4a54-92a5-6b83dec1f504](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/bcab33b0-c04a-452f-b6a7-5978c08b3a50)


### OUTPUT:
![270744231-5b712bd1-29b3-465b-93c0-5076e2aa9128](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/46c0225c-48d4-4a72-8793-af38eff1f02a)

### Q13) Find number of rows in the table EMP

### QUERY:
![270744415-c7af2c72-f955-4cfa-925e-e1768eff217b](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/e27d184b-83ae-4fa3-b4d7-537748036d6d)


### OUTPUT:
![270744469-c5628317-f034-4f88-951c-339f05cd7079](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/b456cfaa-d6bd-4692-81f2-f8458278cb05)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:
![270744958-b50b8a48-eb40-42e5-9fd4-c638757f67ba](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/9a2745e9-c67f-4532-ae99-1f686381c9a3)


### OUTPUT:

![270745021-fa7dd8b3-a982-48f3-b03e-bd7f9152564e](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/e8fb67f1-4151-454b-9447-3481910b3f56)

### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![270745532-16718b1f-b7d9-4fbf-97df-0b4a4e74466c](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/ac0f8772-861c-4648-9c21-c08ede389ecd)


### OUTPUT:

![270745586-123c7d66-c434-4809-8e89-85fefdf37f24](https://github.com/AdhithyaMR/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118834761/f7664cf4-5a48-4d0b-b59a-76af6216f386)

### RESULT:
Thus,the data manipulation language and data control language commands are executed.


