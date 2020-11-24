# DBMS Project


## Introduction
----
Payroll management systems allow automating the process of calculating the amount of money the company’s employee is eligible to earn. It not only calculates the amount of salary of employees, but also calculates the number of hours an employee has worked, monitoring the attendance of employees, the necessary deductions from employee’s salary and the amount of tax the employee and business needs to pay. (Rietsema, Payroll Systems, n.d.)

One of the main advantages of using the payroll management systems is that the workload of the employees has been comparatively lessened, which in a way is a good thing because the calculations of many employees is done automatically. This is a software that is affordable and easy to use by many companies. The software even allows the calculation of the end of service benefits of the employees which is one of the most difficult tasks to be done manually as it may include many deductions and other amounts that can be missed out if calculated manually.

Our topic about payroll management systems creates awareness about how the employees or volunteers face problems when the monetary or compensation is calculated using the payroll management systems. It is especially during the current pandemic situation of Covid-19 where many government and private businesses hired first field responders, volunteers and employees to deal with the situation. Unfortunately, with the payroll system, it was difficult to identify the compensation that these employees deserve as it is unable to identify the number of hours that an employee is compulsory to complete and the number of hours that he has done voluntarily. This creates difficulties in calculating the deserved amount at the end of the month.

---
## **Discussion:**
---
### 1. **Business Requirements**

  * The Payroll System is suggested to Government to be implmented as a social welfare program to benfit low wage labor/employees.
  * The Payroll System is automates payroll process and reduces fees for low wage labor/employees.
  * The Payroll System is applicable to local charities or  private company Companies that have employees with around 1000AED monthly wage.
  * The Payroll System notfies labor/employees/users their avaliable payroll in escrow account accessable through their  unique individual credit cards and their monitered through their unique mobile applicaiton account.
  * The Payroll System takes into consideration thrid party payment processing rates and fees.
  * The Private Companies, Charity Program Companies and Payroll Record System has at least some Workforce that allows them to run their businesses.

### 2. **Database Design**

**Identifying Entities (S2L3 Objective 1)**

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

**(i) Identifying Attributes (S2L3 Objective 2)**

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

IV.Charity

  1. Charity ID

  2. Date joined

  3. Number of employees

  4. Number of volunteers

  5. Number of labors on payroll
  6. Subject

V.Payroll

  1. Payroll ID
  2. Total Payment due
  3. Wage
  4. Details
  5. Bonus Applied
  6. Bonus Amount

VI.Contact Information

  1. City main branch

  2. Emirate main branch

  3. Contact number

  4. Street number main branch

  5. Building number

  6. region

VII.Employees

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

  b. Contractor

    - Contract Start Date
    - Contract End Date
    - Number of terms of payments

  c. Volunteers

    - Volunteer Program name
    - Impact description

  d. Finance

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

**(ii) Identifying Mandatory/Optional Attributes (S2L3 Objective 3)**

The Potential Entities and Attributes including Optionality:

I. Government Programs

  1. \*Program ID
  2. \*Program name

II. Program Applicant

  1. \*Applicant ID
  2. \*Applicant name
  3. \*Application submission date
  4. \*Application status

III. Private Company

  1. \*Company ID

  2. \*Date joined

  3. \*Number of employees

  4. o Number of labors on payroll

IV.Charity

  1. \*Charity ID

  2. \*Date joined

  3. \*Number of employees

  4. \*Number of volunteers

  5. o Number of labors on payroll
  6. o Subject

V.Payroll

  1. \*Payroll ID
  2. \*Total Payment due
  3. \*Wage
  4. o Details
  5. o Bonus Applied
  6. o Bonus Amount

VI.Contact Information

  1. \*City main branch

  2. \*Emirate main branch

  3. \*Contact number

  4. \*Street number main branch

  5. \*Building number

  6. o region

VII.Employees

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

  b. Contractor

    1. \*Contract Start Date
    2. \*Contract End Date
    3. \*Number of terms of payments

  c. Volunteers

    1. \*Volunteer Program name
    2. *o* Impact description

  d. Finance

    1. o Department number
    2. \*Financial performance
    3. o Financial project numbers
    4. o internal cases covered

  e. Management

    1. \*Manager performance
    2. o Number of people managed
    3. o Manager projects
    4. o Department number

VIII. App Account

  1. \*Account number
  2. account balance
  3. wage recieved
  4. total withdrawl date
  5. last withdrawl
IX. credit card
  1. \*Credit card number
  2. \*Credit card expiration date
  3. \*Encrypted wire key for money transfer
  4. \*Transaction number
  5. \*Processing fees
  6. \*Wage received
  7. Credit card back number

X. payroll entity escrow
  1. entity account
  2. number of transactions
  3. processing time

**(iii) Using Barker Notation (S2L3 Objective 4)**

| GOVERNMENT PROGRAMS \*Program ID\*Program name |
| --- |

| PROGRAM APPLICANT \*Applicant ID \*Application submission date \*Is it a Charity Company or Business Company? \*Application status |
| --- |

| PRIVATE COMPANY \*Company ID \*Date joined \*Number of employees\*Number of labors on payroll |
| --- |

| CHARITY  \*Charity ID \*Date joined \*Number of employees \*Number of volunteers\*Number of labors on payroll |
| --- |

| PAYROLL \*Entity account \*Payroll ID \*Total Payment DueoDetails oBonus AppliedoBonus Amount |
| --- |

| CONTACT INFORMATION \*City main branch \*Emirate main branch \*Contact number \*Street number main branch \*Building number\*City district / region |
| --- |

| EMPLOYEES \* Employee ID\* Position \* Start Date\* End Date \* First Name\* Last Name \* Phone number\* Insuranceo Benefitso Bonus |
| --- |

| CONTRACTOR \* Contract Start Date \* Contract End Date \* Number of terms of payments |
| --- |

| VOLUNTEERS \* Volunteer Program name o Impact description |
| --- |

| FINANCE \* Department number \* Head of department \* Financial performance \* Financial project numbers |
| --- |

| MANAGEMENT \* Number of people managed \* Manager performance \* Manager projects \* Head of department \* Department number |
| --- |

| APP ACCOUNT \* Account number \* Credit card number \* Encrypted wire key for money transfer \* Transaction number \* Processing fees \* Wage received o Credit card back numbero Credit card expiration date |
| --- |

1. **Unique Identifiers**

**(i) Identifying Unique Identifiers (UIDs) (S2L4 Objective 1)**

| GOVERNMENT PROGRAMS#Program ID\*Program name |
| --- |

| PROGRAM APPLICANT#Applicant ID\*Application submission date\*Is it a Charity Company or Business Company?\*Application status |
| --- |

| PRIVATE COMPANY#Company ID\*Date joined\*Number of employees\*Number of labors on payroll |
| --- |

| CHARITY#Charity ID\*Date joined\*Number of employees\*Number of volunteers\*Number of labors on payroll |
| --- |

| PAYROLL#Payroll ID\*Entity account\*Total Payment DueoDetailsoBonus AppliedoBonus Amount |
| --- |

| CONTACT INFORMATION\*City main branch\*Emirate main branch\*Contact number\*Street number main branch\*Building number\*City district / region |
| --- |

| EMPLOYEES# Employee ID\* Position\* Start Date\* End Date\* First Name\* Last Name\* Phone number\* Insuranceo Benefitso Bonus |
| --- |

| CONTRACTOR\* Contract Start Date\* Contract End Date\* Number of terms of payments |
| --- |

| VOLUNTEERS\* Volunteer Program nameo Impact description |
| --- |

| FINANCE\* Department number\* Head of department\* Financial performance\* Financial project numbers |
| --- |

| MANAGEMENT\* Number of people managed\* Manager performance\* Manager projects\* Head of department\* Department number |
| --- |

| APP ACCOUNT# Account number\* Credit card number\* Encrypted wire key for money transfer\* Transaction number\* Processing fees\* Wage receivedo Credit card back numbero Credit card expiration date |
| --- |

**(ii) Identifying Artificial Unique Identifiers (UIDs) (S2L4 Objective 2)**

| GOVERNMENT PROGRAMS#Program ID(#) Program name |
| --- |

| PROGRAM APPLICANT#Applicant ID(#) Application submission date\*Is it a Charity Company or Business Company?\*Application status |
| --- |

| PRIVATE COMPANY#Company ID(#) Date joined\*Number of employees\*Number of labors on payroll |
| --- |

| CHARITY#Charity ID(#) Date joined\*Number of employees\*Number of volunteers\*Number of labors on payroll |
| --- |

| PAYROLL#Payroll ID(#) Entity account\*Total Payment DueoDetailsoBonus AppliedoBonus Amount |
| --- |

| CONTACT INFORMATION(#) Contact number\*City main branch\*Emirate main branch\*Street number main branch\*Building number\*City district / region |
| --- |

| EMPLOYEES# Employee ID(#) Phone number\* Position\* Start Date\* End Date\* First Name\* Last Name\* Insuranceo Benefitso Bonus |
| --- |

| CONTRACTOR\* Contract Start Date\* Contract End Date\* Number of terms of payments |
| --- |

| VOLUNTEERS(#) Volunteer Program nameo Impact description |
| --- |

| FINANCE(#) Department number\* Head of department\* Financial performance\* Financial project numbers |
| --- |

| MANAGEMENT(#) Department number\* Number of people managed\* Manager performance\* Manager projects\* Head of department |
| --- |

| APP ACCOUNT# Account number(#) Credit card number\* Encrypted wire key for money transfer\* Transaction number\* Processing fees\* Wage receivedo Credit card back numbero Credit card expiration date |
| --- |

1. **Relationships**

**(i) Recognize Examples of Relationships (S2L5 Objective 1)**



**(iii) Identify the Cardinality of Relationships (S2L5 Objective 3)**



**(iv) Using a Relationship Matrix (S2L5 Objective 5)**

1. **Entity Relationship Modeling (S2L6 Objective 5)**
2. **Relationships Resolving Many to Many Relationships (S3L1 Objective 2)**
3. **Identify and Illustrate Non-Transferable Relationships**
4. **Identify and Draw Supertype and Subtype Entities**
5. **Identify Hierarchical, Recursive and Arc Relationships**
6. **Using Normalization to Validate Data (S3L3 Objective 3)**
7. **Using Normalization to Validate Data**
8. **Using Normalization to Validate Data**
9. **Database Implementation and Testing**
10. **Apply the Rules of Relationship Mapping to Transform Relationship**
11. **Creating a Logical Data Model**
12. **Engineer the Relational Model from the Logical Data Model**

**Results**

**Conclusions**

**Recommendations**

**References**

**Appendices**
---
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

