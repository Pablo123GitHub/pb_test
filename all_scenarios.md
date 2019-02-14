## List of all possible test scenarios 

#### Wrong input 
- The user enters an invalid email address 
- The user enters an email address that does not have any Perkbox account
- The user enters nothing in the input field and click on the CONTINUE button

#### Correct input. We assume that for all tests below, the user enters a valid email address, clicks on Continue, then here are the different scenarios : 

- She selects an account : the URL of the page should be changed with the name of the account that has just been selected. Then we should see the Email address field prepopulated with the initial email address (ACCEPTANCE TEST)
- She does not select an account, and click on the CONFIRM button immediately, an error message should be displayed to give instructions about selecting an account (this is not actually happening, no error message is displayed when we click directly on the CONFIRM button  )
- Upon selecting an account, the selected account loses the ".disabled" class which controls the highlighting/not-highliting of the given account. 




