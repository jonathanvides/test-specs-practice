## Unit Tests
### Prompt 1: A function called "multiplication" that returns the product of the two input numbers.

* Expect multiplication(2,5) to be a number
* Expect multiplication("two", 5) to be an error
* Expect product to be equal to 2 * 5
* Expect product to be a number
* Expect product to be the result of two numbers

### Prompt 2: A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

* Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be equal to an array of numbers
* Expect concatOdds([ ], [ ]) to be two array of numbers
* Expect concatOdds with empty arrays to be returned as an empty array
* Expect concatOdds(["three", 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be an error
* Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be in ascending order
* Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be only odd numbers
* Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be a return of a single array
* Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be removing duplicates and only returning the same number once

## Functional Tests
### Prompt 1: A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

* When a user clicks "Checkout with Log In" without filling in any information, they should be shown an error and prompted to sign up if they have not yet
* When a user clicks "Checkout with Log In" but has used an incorrect login or password, they should be shown an error and prompted to checkout as guest if they do not have a login
* When a user clicks "Log In" and has filled in their login and password correctly, they should be taken to purchase what is in their shopping cart
* When a user clicks "Checkout as Guest", they should be taken to purchase what is in their shopping cart
* When a user clicks "Checkout as Guest", they should be asked if they want to create a login or login with their account if they have one
* When user is sent to their shopping cart and it is empty, they should be prompted to add items to their cart
* When user is sent to their shopping cart and has items, they should be asked if they want to continue shopping or purchase the items in their cart
* When user is purchasing the items in their cart, they should be shown the items and the prices of the items in the cart
* When user is purchasing the items in their cart, they should be asked if they have a referral code to save money and how they will be paying
