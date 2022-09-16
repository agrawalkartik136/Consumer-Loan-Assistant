# Consumer-Loan-Assistant

PROBLEM STATEMENT

(Ever wonder just) How much those credit card accounts are costing you?

ABSTRACT 

This project will help you get a handle on consumer debt. The Consumer Loan Assistant Project you would build computes payments and loan terms given balance and interest infromation. We look at focus traversal among controls, how to do input validation, and the message box for user feedback.

OVERVIEW

In this project, we will build a consumer loan assistant, You input a loan balance and yearly interest rate. You than have two options: (1) Enter the desired number of paymentsand the loan assistant computes the monthly payment, or (2) enter the desired monthly payment and the loan assistant determines the number of payments you will make. An analysis of your loan,including total number of payments and interest rate is also provided.You will see:

![Screenshot_2022-09-16-08-05-46-38_e2d5b3f32b79de1d45acd1fad96fbb0f](https://user-images.githubusercontent.com/73596373/190545131-7ddaa759-4dec-448e-a3d8-842349a0a163.jpg)

All label controls are used for title infromation. Two button controls are used to compute results and to start a new analysis. Two small button controls(marked with X; only one is seen at a time) control whether you compute the number of payments or the payment amount. One button exits the project. Four text field controls are used for inputs and a large text area is used to present the loan analysis results. The loan assistant appears as:

![Screenshot_2022-09-16-08-06-04-88_e2d5b3f32b79de1d45acd1fad96fbb0f](https://user-images.githubusercontent.com/73596373/190545689-cd6664bd-bf9b-45a9-88e6-66f46ab181b2.jpg)

In this initial configuration, you enter a Loan Balance, an interest rate(as percent) and a Number of Payments value. Click compute monthly payment. The payment will appear in the "Yellow" text field and a complete loan analysis will appear in the large text field. Here are some numbers i tried:

![Screenshot_2022-09-16-08-06-20-71_e2d5b3f32b79de1d45acd1fad96fbb0f](https://user-images.githubusercontent.com/73596373/190546051-4c652d11-c548-4a29-98dc-e0a96fb6924e.jpg)

So of if i borrow $10,000 at 5.5% interest I will pay $301.96 for three years(36 months). More specific details on exect payment amounts, including total interest paid, is shown under Loan Analysis. And you can click on New Loan Analysis to try some new values:

Note the Loan Balance, Interest Rate, and Number of Payments entries remain. Only the Monthly Payment and the Loan Analysis have been cleared. This lets you try different values with minimal typing of new entries. Change any entry you like to see different results – or even change them all. Try as many combinations as you like.
At some point, clear the text fields and click the button with an X next to the Number of Payments text field. You will see:

![Screenshot_2022-09-16-08-24-52-46_e2d5b3f32b79de1d45acd1fad96fbb0f](https://user-images.githubusercontent.com/73596373/190547341-f2b2cfdf-3410-486b-a62d-0694d8a5d516.jpg)

Notice the Number of Payments box is now yellow. The button with an X has moved to the Monthly Payment text field. In this configuration, you enter a Loan Balance, an Interest Rate and a Monthly Payment. The loan assistant will determine how many payments you need to pay off the loan. Here are some numbers I tried:
![Screenshot_2022-09-16-08-25-06-41_e2d5b3f32b79de1d45acd1fad96fbb0f](https://user-images.githubusercontent.com/73596373/190547524-5648bdc6-514a-49d4-9a41-9a7e96b0e520.jpg)

It will take 59 payments (the last one is smaller) to pay off this particular loan. Again, you can click New Loan Analysis to try other values and see the results. That’s all you do with the loan assistant project – there’s a lot going on behind the scenes though. The loan assistant has two modes of operation. It can compute the monthly payment, given the balance, interest and number of payments. Or, it can compute the number of payments, given the balance, interest, and payment. The text field representing the computed value is yellow. The button marked X is used to switch from one mode to the next. 
To exit the project, click the Exit button.






