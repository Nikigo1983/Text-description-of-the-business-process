# Text description of the business process "Ordering food from a restaurant":
* **Start** 
* **Step 1** (user:) selects the "Meal Catalog" section on the application screen, clicks on it.
* **Step 2** (system:) displays the food catalog on the screen. 
* **Step 3** (user): adds the dishes from the catalog to the shopping cart and specifies the quantity.
* **Step 4** (system): adds the selected meal choices and their quantities to the shopping cart. 
* **Step 5** (user): moves to the shopping cart.
* **Step 6** (system): moves the user to the shopping cart. 
* **Step 7** (user): if necessary, changes the number of dishes or deletes dishes.
* **Step 8** (system): processes and displays the changes made.
* **Branch 1** (user): wants to edit his order?
  * "Yes" - switch to branch 2 .
  * "No" - proceed to step 7. 
* **Branch 2** (user): where does he want to edit his order?
  * "In shopping cart" - go to step 5.
  * "In catalog" - Skip to step 1. 
* **Step 7** (user): presses the "Checkout" button.
* **Step 8** (system): opens "Delivery address" form. 
* **Step 9** (user): Fills out the form and clicks on the "Confirm Shipping Address" button. 
* **Step 10** (system): shows the calendar window "Select delivery date and time".
* **Step 11** (user): selects a delivery date and time on the calendar and presses the "Confirm" button.
* **Step 12** (system): shows the screen "Choose payment method: pay with bank card now or pay to courier in cash". 
* **Branch 3** (user): which payment method does he choose?
  * "Pay with bank card now" - proceed to step 13.
  * "Pay to courier in cash" - go to step 16.
* **Step 13** (user): click on "Pay with bank card now".
* **Step 14** (system): opens a form to confirm the details of the bank card or select a card from those previously added.
* **Step 15** (user): completes the form and clicks "Pay order".
* **Branch 4** (user): the online payment was successful?
  * "Yes" - proceeds to step 16.
  * "No" - branch 5.
* **Branch 5** (user): try to pay online again?
  * "Yes" - continue to step 14.
  * "No" - pass to step 12. 
* **Step 16** (system): shows the message "Thank you! Your order has been successfully placed. Expect delivery on 11 February 2023 at 15:30".
* **End**