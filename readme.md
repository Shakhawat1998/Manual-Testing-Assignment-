## Manual Testing on Transaction System's Features

## Overview 
This project involves in-depth manual testing of a transaction app's essential financial features. The focus areas include validating merchant payments, utility bill transactions, service charge calculations, cashback rewards, loan processing, and repayment workflows. The scope encompasses defining rule-based acceptance criteria, developing comprehensive test cases, detecting bugs, and prioritizing fixes to ensure transaction accuracy and an excellent user experience.

## Project Scenario 
### Feature 1:
In an MFS mobile app named EasyPay, customers can pay any merchant and utility bills. For each merchant bill payment, a 1% service charge will be deducted from the customer's balance, with a minimum transaction fee of 5 TK. If a customer makes a transaction of more than 5000 TK, they will get a 10% cashback. If the customer makes a transaction of more than 10,000 TK, they will receive a maximum of 20% cashback, with the maximum cashback amount being 3000 TK. But no cashback will be applied for the utility bills.
### Feature 2:
If a customer has a balance of less than 100 tk, s/he can apply for a loan of up to 20000 tk. If the customer repays the loan within 30 days from the loan initiation day, no interest will be charged. However, if the customer fails to repay within this period, a daily interest of 1.8% will be applied in a compound interest manner on the remaining amount.
Additionally, if a customer has already paid 50% of the remaining payment, they are eligible to apply for another loan.

## 1. Acceptance Criteria (Rule-Based Standards)
- Write the acceptance criteria for both **Feature 1** and **Feature 2** based on rule-based standards.

## 2. Test Cases (Positive & Negative)
- Write test cases (Positive & Negative) for **Feature 1** and **Feature 2** in a standard test case format.

## 3. Bug/Improvement Report
- Visit this site and write a minimum of 10 bugs/improvements with appropriate priority and severity.  
  [EasyPay Login URL](https://master.d1zgfbpp372908.amplifyapp.com/login)  
  **Admin login:**  
  - Email: admin@roadtocareer.net  
  - Password: 1234  
  **System user login:**  
  - Email: system@roadtocareer.net  
  - Password: 1234  
  **General Activities You Can Perform:**
  1. Login as admin with the provided credentials.
  2. Admin can create a Customer, Agent, another admin, or merchant.
  3. System user can deposit to an agent.
  4. Agent can deposit or make payments to a merchant.
  5. Customer can withdraw and make payments.
  6. Merchant can only see transaction history of received payments.

## 4. Feature Priority and Explanation
- Write the feature Id serially by its priority level and explain how you have prioritized the features in a Google Doc.  
  Attach the priority table as well.

For detailed documentation, test cases, and bug reports, please click [here](https://drive.google.com/drive/folders/1KmsRl0BONV4Gbb6jxS4SmMGCEG8ikIX5?usp=sharing)
