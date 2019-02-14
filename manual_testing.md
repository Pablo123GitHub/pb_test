## Manutal testing

#### SCENARIO A (ACCEPTANCE TEST)
- User goes to https://app.perkbox.com
the URL should now be https://app.perkbox.com/welcome/login 
- User types the pooja@perkbox.co.uk  email address in the input field 
- User types on the CONTINUE button 
the page should display a div element with class ".tenant" that contains the text “demo-test-france”
- User clicks on the div that contains the text “demo-test-france” with class ".tenant"
- User clicks on the button who contains the text “CONFIRM”
- User is redirected to a page with url : https://demo-test-france.perkbox.com/welcome/login
- the input field with name attribute “email” should contain pooja@perkbox.co.uk already (it has been prepopulated)


### SCENARIO B 

- User goes to https://app.perkbox.com
- The page should NOT display the text  “User is not found” (because the user has done nothing so far)
- User enters an email address that does not belong to Perkbox. For example fake@email.com.
- User clicks on the CONTINUE button
- The error message “User is not found” should be displayed on the page.