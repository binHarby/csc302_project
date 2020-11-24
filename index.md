# DBMS Payroll Project

> Abdulla Alameri 1070401
> Areesha Ahmed 1049798
> Administered by Dr. Adel Khelifi


## Introduction
----
Payroll management systems allow automating the process of calculating the amount of money the company’s employee is eligible to earn. It not only calculates the amount of salary of employees, but also calculates the number of hours an employee has worked, monitoring the attendance of employees, the necessary deductions from employee’s salary and the amount of tax the employee and business needs to pay. (Rietsema, Payroll Systems, n.d.)

One of the main advantages of using the payroll management systems is that the workload of the employees has been comparatively lessened, which in a way is a good thing because the calculations of many employees is done automatically. This is a software that is affordable and easy to use by many companies. The software even allows the calculation of the end of service benefits of the employees which is one of the most difficult tasks to be done manually as it may include many deductions and other amounts that can be missed out if calculated manually.

Our topic about payroll management systems creates awareness about how the employees or volunteers face problems when the monetary or compensation is calculated using the payroll management systems. It is especially during the current pandemic situation of Covid-19 where many government and private businesses hired first field responders, volunteers and employees to deal with the situation. Unfortunately, with the payroll system, it was difficult to identify the compensation that these employees deserve as it is unable to identify the number of hours that an employee is compulsory to complete and the number of hours that he has done voluntarily. This creates difficulties in calculating the deserved amount at the end of the month.

---
## **Discussion:**
---
### 1. **Business Requirements**

  1. The Payroll System is suggested to Government to be implmented as a social welfare program to benfit low wage labor/employees.
  2. The Payroll System is automates payroll process and reduces fees for low wage labor/employees.
  3. The Payroll System is applicable to local charities or  private company Companies that have employees with around 1000AED monthly wage.
  4. The Payroll System notfies labor/employees/users their avaliable payroll in escrow account accessable through their  unique individual credit cards and their monitered through their unique mobile applicaiton account.
  5. The Payroll System takes into consideration thrid party payment processing rates and fees.
  6. The Private Companies, Charity Program Companies and Payroll Record System has at least some Workforce that allows them to run their businesses.

### 2. **Database Design**

**Identifying Entities**

  1. Government Programs
  2. Program Applicant
  3. Private Company
  4. Charity
  5. Payroll Record
  6. Contact Information
  7. Employees
    * finance
    * managment
    * volunteer
    * contractor
  8. Application Account
  9. payroll escrow account
  10. credit card



---
---


### **2.1 Entities and Attributes**

**Identifying Attributes**

I. Government Programs

  1. Program ID
  2. Program name

II. Program Applicant

  1. Applicant ID
  2. Applicant name
  3. Application submission date
  4. Application status

III. Private Company

  1. Company ID

  2. Date joined

  3. Number of employees

  4. Number of labors on payroll

IV. Charity

  1. Charity ID

  2. Date joined

  3. Number of employees

  4. Number of volunteers

  5. Number of labors on payroll
  6. Subject

V.  Payroll

  1. Payroll ID
  2. Total Payment due
  3. Wage
  4. Details
  5. Bonus Applied
  6. Bonus Amount

VI. Contact Information

  1. City main branch

  2. Emirate main branch

  3. Contact number

  4. Street number main branch

  5. Building number

  6. region

VII. Employees

  - Employee ID
  - Position Title
  - Start Date
  - End Date
  - First Name
  - Last Name
  - Phone number
  - Insurance covered
  - Benefits
  - Bonus

  1. Contractor

   - Contract Start Date
   - Contract End Date
   - Number of terms of payments

  2. Volunteers

   - Volunteer Program name
   - Impact description

  3. Finance

   - Department number
   - Financial performance
   - Financial project numbers
   - internal cases covered

  e. Management

   - Manager performance
   - Number of people managed
   - Manager projects
   - Department number

VIII. App Account

  1. Account number
  2. Credit card number
  3. Credit card expiration date
  4. Encrypted wire key for money transfer
  5. Transaction number
  6. Processing fees
  7. Wage received
  8. Credit card back number

**Identifying Mandatory/Optional Attributes**

The Potential Entities and Attributes including Optionality:



I. Government Programs

![](https://i.imgur.com/aPdnpYo.png)

  1. \*Program ID
  2. \*Program name



II. Program Applicant

![](https://i.imgur.com/eftUrBE.png)

  1. \*Applicant ID
  2. \*Applicant name
  3. \*Application submission date
  4. \*Application status

III. Private Company

![](https://i.imgur.com/Tge8Hyg.png)

  1. \*Company ID

  2. \*Date joined

  3. \*Number of employees

  4. o Number of labors on payroll

IV. Charity

![](https://i.imgur.com/fdTrAzs.png)

  1. \*Charity ID

  2. \*Date joined

  3. \*Number of employees

  4. \*Number of volunteers

  5. o Number of labors on payroll
  6. o Subject

V. Payroll



  1. \*Payroll ID
  2. \*Total Payment due
  3. \*Wage
  4. o Details
  5. o Bonus Applied
  6. o Bonus Amount

VI. Contact Information

![](https://i.imgur.com/JQc61MY.png)

  1. \*City main branch

  2. \*Emirate main branch

  3. \*Contact number

  4. \*Street number main branch

  5. \*Building number

  6. o region

VII. Employees

![](https://i.imgur.com/mwUXjE0.png)

  1. \*Employee ID
  2. \*Position Title
  3. \*Start Date
  4. \*End Date
  5. \*First Name
  6. \*Last Name
  7. \*Phone number
  8. \*Insurance covered
  9. o Benefits
  10. o Bonus



  1. Contractor

   1. \*Contract Start Date
   2. \*Contract End Date
   3. \*Number of terms of payments

  2. Volunteers

   1. \*Volunteer Program name
   2. *o* Impact description

  3. Finance

   1. o Department number
   2. \*Financial performance
   3. o Financial project numbers
   4. o internal cases covered

  3. Management

   1. \*Manager performance
   2. o Number of people managed
    3. o Manager projects
    4. o Department number

VIII. App Account

![](https://i.imgur.com/MzqpalH.png)

  1. \*Account number
  2. account balance
  3. wage recieved
  4. total withdrawl date
  5. last withdrawl

IX. credit card

![](https://i.imgur.com/fVSXW9y.png)

  1. \*Credit card number
  2. \*Credit card expiration date
  3. \*Encrypted wire key for money transfer
  4. \*Transaction number
  5. \*Processing fees
  6. \*Wage received
  7. \*Credit card back number

X. payroll entity escrow

![](https://i.imgur.com/34Ds9W4.png)


  1. \*entity account
  2. \*number of transactions
  3. \*processing rate

**Using Barker Notation**

We used Barker Notation to represent the tables and their columns as entities and their attributes. We followed the logical sequence of the buisness requiremets and the overall intended funciton of the suggested social program as guide while building the database system.

![](https://i.imgur.com/nAYlyEU.png)

**Unique Identifiers**

**Identifying Unique Identifiers & Artificial Unique Identifiers (UIDs)**
  * if a unique identefer is a information bearing whether a primary key, foregin key or a canidate key it becomes a natural key.

  * if a unique identefier is made-up of more then one attribute, that combined makes the entity unique identfier then its becomes a composite unique indentfier.

  * If no information bearing identifier has been assigned then assign an artificial one.  Normally we use id or number as the name for the artificial identifier.

  * if a natural unique identifier exists alogn with an artifical one, one can make a composite key of both as primery entity identifiers.


### **Relationships**


  Relationships demonstrate to a connection between two entities. Identifying clear business rules, helps in Identifying possible relationship between entities.

### **Recognize Examples of Relationships & Identify the Cardinality of Relationships**

  A relationship is a connection between two entities and must either be mandatory or optional.

#### **Business Requirements**

  1. The Payroll System is suggested to Government to be implmented as a social welfare program to benfit low wage labor/employees.
  2. The Payroll System is automates payroll process and reduces fees for low wage labor/employees.
  3. The Payroll System is applicable to local charities or  private company Companies that have employees with around 1000AED monthly wage.
  4. The Payroll System notfies labor/employees/users their avaliable payroll in escrow account accessable through their  unique individual credit cards and their monitered through their unique mobile applicaiton account.
  5. The Payroll System takes into consideration thrid party payment processing rates and fees.
  6. The Private Companies, Charity Program Companies and Payroll Record System has at least some Workforce that allows them to run their businesses.


![](https://i.imgur.com/3jXc5Hh.png)
![](https://i.imgur.com/RGM2asw.png)
![](https://i.imgur.com/PS1VuaC.png)
![](https://i.imgur.com/UAEazGV.png)
![](https://i.imgur.com/MS4xulH.png)


### **Using a Relationship Matrix**

  * A relationship matrix demonstrates how every entity on the far left column behaves toward the entity which it acrosses at the top of the matrix row.
  * If there is a relationship between the interseted entities on the table, then a relationship defination is written.
  * An entiity relationship with itself is written at the in one of the diagnoal boxes, which is also called a recursive relationship


![](https://i.imgur.com/WPaNqbl.png)

### 3. **Entity Relationship Modeling**
  An Entity Relationship Diagram (ERD) allows you to graphical represent the system information and has the following four goals:•Capture all required information.•Ensure that information appears only once.•Model no information that is derivable from other information that is already modeled.•Locate information in a predictable, logical place.As you have already Identified the entities, their attributes and the relationships between the entities you can now begin to construct the finalised ERD that will show how the system is linked together.

**Relationships Resolving Many to Many Relationships**

  In relational databases you can have the following three types of relationship that represent the information requirements and the rules of the business.:•Many-to-one (M:1) or one-to-many (1:M)•Many-to-many (M:M)•One-to-one (1:1)If you have any many to many (M:M) relationships in your ERD then you will need to resolve those before going any further.   Remember you resolve a M:M relationship by: •Delete the M:M relationship.•Create a new entity (intersection). •Create two identifying relationships with the many side on the new intersection entity.
 •Identify and create additional attributes in the intersection entity if   required.  Think about how you would store how many of each item and how many items were actually shipped to the customer.•Evaluate whether the two existing identifying relationships constitute a UID for the intersection entity or whether an artificial UID has to be created for the new entity.•Add relationship labels to the new identifying relationships

 We resolved Many-to-many relationships through making intersection entities, specfically for our Payroll System, payroll_record and payroll_entitiy_escrow intersection entities.

**Identify and Illustrate Non-Transferable Relationships**
This step uses the additional scenario and meeting transcript that was provided in the previous exercise.A non-transferable relationship cannot be moved between instances of the entities it connects and has to be mandatory.

in our payroll system we demonstrate such a relationship with the relationship between contact_info and dont_worry_program_applicant entities.
  ![](https://i.imgur.com/3jXc5Hh.png)
**Identify and Draw Supertype and Subtype Entities**
This step uses the additional scenario and meeting transcript that was provided in previous exercises.Subtype/supertypes allow you to represent entities that have common attributes as a group.•Each subtype is a specialization of a supertype and therefore must be enclosed within an entity.•The common attributes and relationships for all subtypes must be listed only in the supertype, but they are inherited in every subtype.•A subtype can and would generally have attributes and relationships of its own.•There can never be just one subtype; another subtype should be created to contain the rest.

**Identify Hierarchical, Recursive and Arc Relationships**
An arc is an exclusive relationship group, which is defined such that only one of the relationships can exist for any instance of an entity.

**Using Normalization to Validate Data**
Normalization is a relational database concept, but its principles apply to data modeling.

* First Normal Form (1NF) -The data is atomic (All attributes must be single-valued). -The entries in a column are of the same type.-There can be no duplicated rows in the table meaning that the table has a group of columns that uniquely identifies the row.
* Second Normal Form (2NF) -The data meets the requirements for 1NF.-Requires that any non-UID attribute be dependent on the entire UID-If the data is not directly dependent on the entire UID, then it needs to be moved to another table.
* Third Normal Form (3NF) -It met all database requirements for both 1NF and 2NF.-No non-UID attribute can be dependent on another non-UID attribute.-Each column must depend directly on the UID. All attributes that are not dependent on the UID must be removed. For example, attributes that can be derived from data contained in other fields and tables must be eliminated. (All transitive dependencies are eliminated).

**Database Implementation and Testing**
## Tables

```sql

create table GOVERNMENT_PROGRAM (
  program_id        number(12) GENERATED ALWAYS as IDENTITY(START with 100 INCREMENT by 1),
  program_name          varchar2(50) NOT NULL,
  constraint pk_government_program primary key (program_id)
);
create table DONT_WORRY_PROGRAM_APPLICANT (
  program_id          number(12) NOT NULL,
  applicant_id        number(10) GENERATED ALWAYS as IDENTITY(START with 10 INCREMENT by 1),
  applicant_sub_date          date NOT NULL,
  applicant_name          varchar2(50) NOT NULL,
  applicant_status          varchar2(12) NOT NULL,
  constraint fk_government FOREIGN KEY (program_id) REFERENCES GOVERNMENT_PROGRAM (program_id),
  constraint pk_program_applicant primary key (program_id,applicant_id)

);
create table CONTACT_INFO (
    program_id              number(12) NOT NULL,
  applicant_id               number(10) NOT NULL,
  city_main_branch          varchar2(50) NOT NULL,
  emirate          varchar2(50) NOT NULL,
  contact_number          number(20) NOT NULL,
  street_main_branch         varchar2(50) NOT NULL,
  building_main_branch          varchar2(50) NOT NULL,
  region_main_branch          varchar2(50) NOT NULL,
  constraint fk_applicant_info FOREIGN KEY (applicant_id,program_id) REFERENCES DONT_WORRY_PROGRAM_APPLICANT (applicant_id,program_id),
  constraint pk_contact_info primary key (applicant_id,program_id)

);
create table PRIVATE_COMPANY (
    company_id      number(10) GENERATED ALWAYS as IDENTITY(START with 2030 INCREMENT by 1),
    applicant_id    number(12) NOT NULL,
    program_id          number(12) NOT NULL,
    date_joined     date NOT NULL,
    num_employees   number NOT NULL,
    num_paid_labor  number,

    constraint fk_applicant_company FOREIGN KEY (applicant_id,program_id) REFERENCES DONT_WORRY_PROGRAM_APPLICANT (applicant_id,program_id),
    constraint pk_company primary key (applicant_id,program_id,company_id)


);

create table CHARITY (
    program_id              number(12) NOT NULL,
  applicant_id               number(10) NOT NULL,
  charity_id                number(10) GENERATED ALWAYS as IDENTITY(START with 1101 INCREMENT by 1),
  num_employees   number NOT NULL,
  num_volunteers   number NOT NULL,
    num_paid_labor  number,
    subject_       varchar2,
  constraint fk_applicant_charity FOREIGN KEY (applicant_id,program_id) REFERENCES DONT_WORRY_PROGRAM_APPLICANT (applicant_id,program_id),
  constraint pk_charity primary key (applicant_id,program_id,charity_id )

);
create table EMPLOYEE (
    program_id              number(12) NOT NULL,
  applicant_id               number(10) NOT NULL,
  company_id      number(10) NOT NULL,
  emp_id                number(8) GENERATED ALWAYS as IDENTITY(START with 1 INCREMENT by 1),
    position_title  varchar2(50) NOT NULL,
    rolling_payment_period  varchar2(50) NOT NULL,
    startt_date              date NOT NULL,
    end_date                  date NOT NULL,
    first_name                varchar2(20) NOT NULL,
    last_name                varchar2(20) NOT NULL,
    phone_num                number NOT NULL,
    benfits                   number,
    bonus                     number,
    insurance_covered        char(1) check (insurance_covered in ( 'Y', 'N' )) NOT NULL,

  constraint fk_company_employee FOREIGN KEY (company_id,applicant_id,program_id) REFERENCES PRIVATE_COMPANY (company_id,applicant_id,program_id),
  constraint pk_employee primary key (company_id,emp_id,applicant_id,program_id)

);

create table FINANCE (
    program_id              number(12) NOT NULL,
  applicant_id               number(10) NOT NULL,
  emp_id                number(8),
  company_id      number(10) NOT NULL,
   position_title  varchar2(50) NOT NULL,
    rolling_payment_period  varchar2(50) NOT NULL,
    startt_date              date NOT NULL,
    end_date                  date NOT NULL,
    first_name                varchar2(20) NOT NULL,
    last_name                varchar2(20) NOT NULL,
    phone_num                number NOT NULL,
    benfits                   number,
    bonus                     number,
    insurance_covered        char(1) check (insurance_covered in ( 'Y', 'N' )) NOT NULL,
  department_num   number,
  internal_cases_covered   number,
    fin_preformance  varchar2(50) NOT NULL,
    fin_project_num number,
  constraint fk_company_emp_finance FOREIGN KEY (emp_id,company_id,applicant_id,program_id) REFERENCES EMPLOYEE (emp_id,company_id,applicant_id,program_id),
  constraint pk_finance primary key (emp_id,company_id,applicant_id,program_id)

);
create table MANAGMENT (
    program_id              number(12) NOT NULL,
  applicant_id               number(10) NOT NULL,
  company_id      number(10) NOT NULL,
  emp_id                number(8),
   position_title  varchar2(50) NOT NULL,
    rolling_payment_period  varchar2(50) NOT NULL,
    startt_date              date NOT NULL,
    end_date                  date NOT NULL,
    first_name                varchar2(20) NOT NULL,
    last_name                varchar2(20) NOT NULL,
    phone_num                number NOT NULL,
    benfits                   number,
    bonus                     number,
    insurance_covered        char(1) check (insurance_covered in ( 'Y', 'N' )) NOT NULL,
  department_num   number,
  people_managed   number,
    mgr_preformance  varchar2(50) NOT NULL,
    mgr_projects_num number,
  constraint fk_company_emp_mana FOREIGN KEY (emp_id,company_id,applicant_id,program_id) REFERENCES EMPLOYEE (emp_id,company_id,applicant_id,program_id),
  constraint pk_mana primary key (emp_id,company_id,applicant_id,program_id)
);
create table VOLUNTEER (
    program_id              number(12) NOT NULL,
  applicant_id               number(10) NOT NULL,
  company_id      number(10) NOT NULL,
  emp_id                number(8),
   position_title  varchar2(50) NOT NULL,
    rolling_payment_period  varchar2(50) NOT NULL,
    startt_date              date NOT NULL,
    end_date                  date NOT NULL,
    first_name                varchar2(20) NOT NULL,
    last_name                varchar2(20) NOT NULL,
    phone_num                number NOT NULL,
    benfits                   number,
    bonus                     number,
    insurance_covered        char(1) check (insurance_covered in ( 'Y', 'N' )) NOT NULL,
    vol_program  varchar2(50) NOT NULL,
    impact_description varchar2(50),
  constraint fk_company_emp_vol FOREIGN KEY (emp_id,company_id,applicant_id,program_id) REFERENCES EMPLOYEE (emp_id,company_id,applicant_id,program_id),
  constraint pk_vol primary key (emp_id,company_id,applicant_id,program_id)

);
create table CONTRACTER (
    program_id              number(12) NOT NULL,
  applicant_id               number(10) NOT NULL,
  company_id      number(10) NOT NULL,
  emp_id                number(8),
   position_title  varchar2(50) NOT NULL,
    rolling_payment_period  varchar2(50) NOT NULL,
    startt_date              date NOT NULL,
    end_date                  date NOT NULL,
    first_name                varchar2(20) NOT NULL,
    last_name                varchar2(20) NOT NULL,
    phone_num                number NOT NULL,
    benfits                   number,
    bonus                     number,
    insurance_covered        char(1) check (insurance_covered in ( 'Y', 'N' )) NOT NULL,
    contract_start_date  date NOT NULL,
    contract_end_date  date NOT NULL,
    number_of_terms  number(3) NOT NULL,
    terms_amount     number NOT NULL,
    contract_total_value  number,
  constraint fk_company_emp_contracter FOREIGN KEY (emp_id,company_id,applicant_id,program_id) REFERENCES EMPLOYEE (emp_id,company_id,applicant_id,program_id),
  constraint pk_contractor primary key (emp_id,company_id,applicant_id,program_id)
);
create table PAYROLL_RECORD (
    program_id              number(12) NOT NULL,
  applicant_id               number(10) NOT NULL,
  company_id      number(10) NOT NULL,
  emp_id                number(8),
  payroll_id      number(19) GENERATED ALWAYS as IDENTITY(START with 3030 INCREMENT by 1),
    total_payment_due  number NOT NULL,
    wage  number NOT NULL,
    details  varchar2(80) NOT NULL,
    bonus_applied     char(1) check (bonus_applied in ( 'Y', 'N' )),
    bonus_amount  number,
  constraint fk_company_emp_payroll FOREIGN KEY (emp_id,company_id,applicant_id,program_id) REFERENCES EMPLOYEE (emp_id,company_id,applicant_id,program_id),
  constraint pk_payroll primary key (payroll_id,emp_id,company_id,applicant_id,program_id)
);
create table APPLICATION_ACCOUNT (
    program_id              number(12) NOT NULL,
  applicant_id               number(10) NOT NULL,
  company_id      number(10) NOT NULL,
  emp_id                number(8) NOT NULL,
  payroll_id      number(19) NOT NULL,
  account_id      number (19) GENERATED ALWAYS as IDENTITY(START with 6636 INCREMENT by 1),
    total_payment_due  number NOT NULL,
    wage  number NOT NULL,
    details  varchar2(80) NOT NULL,
    bonus_applied     char(1) check (bonus_applied in ( 'Y', 'N' )),
    bonus_amount  number,
  constraint fk_company_emp_payroll_account FOREIGN KEY (payroll_id,emp_id,company_id,applicant_id,program_id) REFERENCES PAYROLL_RECORD (payroll_id,emp_id,company_id,applicant_id,program_id),
  constraint pk_escrow primary key (account_id)
);
create table PAYROLL_ENTITY_ESCROW (
    program_id              number(12) NOT NULL,
  applicant_id               number(10) NOT NULL,
  company_id      number(10) NOT NULL,
  emp_id                number(8) NOT NULL,
  payroll_id      number(19) NOT NULL,
  account_id      number (19) NOT NULL,
  entity_account      number(10) GENERATED ALWAYS as IDENTITY(START with 1221 INCREMENT by 1),
    number_of_trans_processed  number NOT NULL,
  constraint fk_company_emp_payroll_escrow FOREIGN KEY (payroll_id,emp_id,company_id,applicant_id,program_id) REFERENCES PAYROLL_RECORD (payroll_id,emp_id,company_id,applicant_id,program_id),
  constraint fk_account_escrow FOREIGN KEY (account_id) REFERENCES APPLICATION_ACCOUNT(account_id),
  constraint pk_escrow primary key (entity_account,payroll_id,emp_id,company_id,applicant_id,program_id,account_id)
);

create table CREDIT_CARD (
  account_id      number (19),
  credit_card_num   number(16) GENERATED ALWAYS as IDENTITY(START with 6636 INCREMENT by 1),
  credit_card_exp   date NOT NULL,
  credit_card_back_num  number(3)  NOT NULL,
  processing_rate       decimal NOT NULL,
  wage_recieved     char(1) check (wage_recieved in ( 'Y', 'N' )),
  last_withdrawl_date   date NOT NULL,
  last_withdrawl_amount  number NOT NULL,
  constraint fk_account_card FOREIGN KEY (account_id) REFERENCES APPLICATION_ACCOUNT (account_id),
  constraint pk_card primary key (account_id)

);


```
```sql
insert into GOVERNMENT_PROGRAM (program_name) values
   ('Dont worry program');
insert into GOVERNMENT_PROGRAM (program_name) values
   ('water saving program');
insert into GOVERNMENT_PROGRAM (program_name) values
   ('electricity saving program');

insert into DONT_WORRY_PROGRAM_APPLICANT  (program_id,applicant_sub_date,applicant_name,applicant_status) values (
100,TO_DATE('12/01/2020', 'DD/MM/YYYY'),'abdulla company','pending..'

);
insert into CONTACT_INFO  (program_id,applicant_id,city_main_branch,emirate,contact_number,street_main_branch,building_main_branch,region_main_branch) values (
100,10,'Abu Dhabi','bani yas', 0506013322,'80th w','#6','west'

);
insert into PRIVATE_COMPANY  (program_id,applicant_id,date_joined,num_employees) values (
100,10,TO_DATE('11/01/2020', 'DD/MM/YYYY'),100

);
insert into EMPLOYEE  (program_id,applicant_id,company_id,position_title,rolling_payment_period,startt_date,end_date,first_name,last_name,phone_num,benfits,bonus,insurance_covered) values (
100,10,2030,'head of finance','Monthly',TO_DATE('12/01/2020', 'DD/MM/YYYY'),TO_DATE('12/01/2021', 'DD/MM/YYYY'),'Abdulla','Alameri',0501111111,500000,5000,'Y'


);


```
**Creating a Logical Data Model**
![](https://i.imgur.com/nAYlyEU.png)
**Engineer the Relational Model from the Logical Data Model**
  1. **add relational pics here**

---


### **Results**



### **Conclusions**


