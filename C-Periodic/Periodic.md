# **Payroll**

| [PayGroup](#paygroup) | [Transaction](#transaction) | [Periodic](#periodic) | [Setup](#setup) | [Master](#master) | [Accural Setup](#accural-setup) | [PayPeriod](#payperiod) |

<br>

# **[Periodic](#payroll)**

| [Timesheet](#tim) | [RPL Payment Request](#prl-payment-request) | [Individual Payroll](#individual-payroll) | [Salary](#salary) | [Individual Salary]() |

<br>

> ## **[Timesheet](#periodic)**

User can view the Business Payroll/timesheet of Current month or Previous or All in the separate tab.

## **Current**

  - **PayGroup Filter -** By using this filter to view the specific paygroup's current month payroll list.

  - **Current Month Business Payroll -** This can view the filtered specific paygroup's current month payroll list.

    - **User can take action to enable the process,**

      - _The action field is following to,_
    
        **1**- **[Start]()** - Start action to enable or start the salary or transaction payroll.

        **2**- **[Import]()** - Import action to import any new payroll data for the specific paygroup.

        **3**- **[Submit]()** - Submit action to done the import payroll data changes for the specific paygroup.

        **4**- **[Restart]()** - Restart action to re-enable or re-start the salary or transaction payroll incase of stopped or by any error.

        **5**- **[ReEnter]()** - ReEnter action to done the changes or correction made in the payroll data.

        **6**- **[Retry]()** - Retry action to push again any fail or unsuccessful things happen.

        **7**- **[Export]()** - Export action to export any paygroup data.

## **Previous**        

  - **PayGroup Filter -** By using this filter to view the specific paygroup's previous month payroll list.

  - **Previous Month Business Payroll -** This can view the filtered specific paygroup's previous month payroll list.

  - **Payroll Preview -** User can view the payroll preview data in the payroll details page and it includes all payroll and salary details of an employee.

    - **User can take action to move payroll to the Allow Zero Salary stage,**

      - _The action field is following to,_

        **1**- **[Allow Zero Salary]()** - This action to make an employee's payroll to Allow Zero Salary.

## **All**

  - **PayGroup Filter -** By using this filter to view the specific paygroup's all business payroll list.

  - **PayPeriod Filter -** By using this filter to view the specific paygroup's all business payroll list in the specific period of time.

  - **All Business Payroll -** User can view the All Business payroll list by using the paygroup and payperiod filter.

| [Home](#payroll) | [Main](#periodic) | [Back](#timesheet) |       

> ## **[PRL Payment Request](#timesheet)**

The list of data is employee's salary payment request list and this payment request data will move stage by stage.

| [Show Pending](#show-pending) > [Approval](#approval) > [Import](#import) > [Posting](#posting) > [Rejected](#rejected) > [Completed](#completed) |

- ## **Show Pending :**

  - It shows the Pending Payment Request or Rejected Payment request list, from the employees.

- ## **Approval :**

  - It shows the payment request list for an approval and take action to move the payment request stage.

    - _The action field is following to,_

      **1**- **[Complete]()** - User take **Complete** action to move to the **Import** stage.

      **2**- **[Reject]()** - User take **Reject** action to move to the **Rejected** stage.

- ## **Import :** 

  - Approval completed payment requests are listed in the import stage, take action to move the payment request to next stage.

    - _The action field is following to,_

      **1**- **[Complete]()** - User take **Complete** action to move to the **Posting** stage.

      **2**- **[Reject]()** - User take **Reject** action to move to the **Rejected** stage.

      **3**- **[Complete without Posting]()** - User take **Complete without Posting** action to skip the posting stage and directly move to the **Completed** stage.

      **4**- **[Import]()** - Import action to import the excel file to update the bulk data.

- ## **Posting :**

  - Once the Payment Requests are completed the Import stage, it will come to the posting stage. In posting stage,no need to take action to move the payment request to the next stage, it will run by the scheduler automatically.

- ## **Rejected :**

  - This shows the list of rejected payment requests from the previous stages.

- ## **Completed :** 

  - This shows the list of completed payment requests from the posting stage.

| [Home](#payroll) | [Main](#periodic) | [Back](#prl-payment-request) |

> ## **[Individual Payroll](#prl-payment-request)**

User can view the Individual payroll list of Current month or Previous or All in the separate tab.

## **Current**

  - This will view the current month individual payroll list.

    - **User can take Start payroll to enable the payroll automation,**

      - _The action field is following to,_

        **1**- **[Start Payroll]() -** By enable this action, the payroll automation will start running.

        **2**- **[Post]() -** Post action button to dispense the salary to the employee.

## **Previous**

  - This will view the previous month individual payroll list.

    - **User can take Start payroll to enable the payroll automation,**

      - _The action field is following to,_

        **1**- **[Start Payroll]() -** By enable this action, the payroll automation will start running.

        **2**- **[Post]() -** Post action button to dispense the salary to the employee.

## **All**

  - This will view the all period of individual payroll list.

  - **Pay Period -** This filter is used to filter the payroll to view the specific date period of individual payroll. 

    - **User can take Start payroll to enable the payroll automation,**

      - _The action field is following to,_

        **1**- **[Start Payroll]() -** By enable this action, the payroll automation will start running.

        **2**- **[Post]() -** Post action button to dispense the salary to the employee.

| [Home](#payroll) | [Main](#periodic) | [Back](#individual-payroll) |

> ## **[Salary](#individual-payroll)**

## **Current**

  - **PayGroup Filter -** By using this filter to view the specific paygroup and that data will reflect in the current salary table.

  - **Current Salary -** It shows the paygroup current salary filtered data.

## **Previous**

  - **Previous Salary with Paygroup Filter -** User can view the previous month salary of the specific paygroup by using the paygroup filter.

## **All**

 - **All Salary with Filter -** User can view all salary of the specific Payperiod and Paygroup by filtering it.

| [Home](#payroll) | [Main](#periodic) | [Back](#salary) |

> ## **[Individual Salary](#salary)**

  - **Individual Salary by Payperiod Filter -** User can use this filter to view the specific Payperiod of Individual salary list.

    - **User can filter the table data by their preference and use action to update the salary data,**

    **1**- **[Bank]() -** Using this filter to view the salary transfer via bank.

    **2**- **[Cash]() -** Using this filter to view the salary given by hard cash.

    **3**- **[Update Payment Status - By RecId/By Employee Id]() -** User used this action to edit and update the individual salary data.

| [Home](#payroll) | [Main](#periodic) | [Back](#individual-salary) |