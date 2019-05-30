# Hibernate-Table-Per-Subclass-Using-Annotation

Hibernate: select hibernate_sequence.nextval from dual

Hibernate: select hibernate_sequence.nextval from dual

Hibernate: select hibernate_sequence.nextval from dual

Hibernate: insert into table_per_subclass_employee (name, id) values (?, ?)

Hibernate: insert into table_per_subclass_employee (name, id) values (?, ?)

Hibernate: insert into table_per_subclass_emp_reg (bonus, salary, ID) values (?, ?, ?)

Hibernate: insert into table_per_subclass_employee (name, id) values (?, ?)

Hibernate: insert into table_per_subclass_emp_ctr (contract_duration, pay_per_hour, ID) values (?, ?, ?)

SQL> select * from table_per_subclass_employee;

	ID NAME
	30 jis
	31 joe
	32 jil

SQL> select * from table_per_subclass_emp_reg;

	ID     SALARY	   BONUS
	31	50000	       5

SQL> select * from table_per_subclass_emp_ctr;

	ID PAY_PER_HOUR CONTR
	32	   1000 15 hr

