# Block18.WritingTestSpecs

## Unit Tests
### Multiplication
- expect multiplication(3, 4) to be numbers
- expect multiplication(3, 4) to return a number
- expect multiplication(3, 4) to return the number 12
- expect multiplication("x", 4) to be an error
### contOdds
- expect contOdds to return a single array
- expect contOdds to return only odd numbers
- expect contOdds to return the odd numbers in ascending order
- expect contOdds to return an error message if there are letters or strings in the array
- expect contOdds to return only one of each odd number


## Functional Test
- When a user clicks "add item to cart" the cart should update with the item without a page refresh
- when a user clicks the shopping cart icon they should be taken to their cart with all of their items
- when the user clicks checkout they should be taken to a checkout page
- if the user clicks checkout and there are no items in the cart an error message should pop up
- when the user is on the checkout page there should be an option to either sign in or continue as guest
- if the user clicks "sign in" they should be taken to a sign-in form
- sign in form should ask for the user's email and password
- when the information is entered correctly and the user clicks "sign in" they will be taken back to the checkout page and can fill out the checkout form
- if the information is entered incorrectly and the user clicks "sign in" an error message will pop up and they will not be taken back to the checkout page.
- when the user clicks "continue as guest" they will be given a form to enter in their email
- if the guest enters their email correcly and clicks "continue", they will be able to fill out the rest of the checkout form
- if the guest does not enter  their email correctly and clicks "continue" an error message will pop up and they will not be able to fill out the form until the email is correctly entered
