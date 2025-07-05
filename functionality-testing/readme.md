1.) Verify product addition to the shopping cart	
Ans-> 
Precondition:
a) User Should be Logged in the Account
b) Product is in Stock

Test Steps:
a) Open the Product Page.
b) Choose the Desired Quantity and variant(if displayed)
c) Click On Add to Cart Button

Expected Result:
product is added to the shopping cart with updated quantity.

Pass/Failed Criteria:
product is added to the shopping cart with updated quantity.

2.) Verify Login Requirement Before Checkout
Ans->
Precondition:
a) User should not be logged in.

Test Steps:
a) Open the Product Page.
b) Click on Add to Cart Button.
c) Open the Cart Page.
d) Click on Checkout Button.

Expected Result:
Redirected to Login/Signup Page.

Pass/Failed Criteria:
a)Pass- Redirected to Login/Signup Page.
b)Fail- User does not gets Redirected to Login/Signup Page.

3.)Verify Discount Coupon Application
Ans->
Precondition:
a) Cart should have Valid Products.

Test Steps:
a) Open the Product Page.
b) Click on Add to Cart Button.
c) Open the Cart Page.
d) Apply the Promo Code.

Expected Result:
User should get to the Checkout Page where the Product is displayed with applied Promo Code.

Pass/Failed Criteria:
a)Pass- Promo Code is applied in the Total Amount.
b)Fail- Promo Code is not applied in the Total Amount.

4.) Verify Price Update with Variant Selection
Ans->
Precondition:
a) Product should contain Variants.

Test Steps:
a) Open the Product Page.
b) Choose the Desired Variant by Clicking on it.

Expected Result:
User gets to see a change in the Product Pricing Because of the change in the Variant of the Product.

Pass/Failed Criteria:
a)Pass- Product pricing is Updated.
b)Fail- Product pricing is not Updated.

5.) Verify Login Functionality.
Ans->
Precondition:
a)User is registered and has valid login credentials (email/username and password).
b)The login page is accessible.

Test Steps:
a) Go to Login Page.
b) Enter Valid Username/E-mail/Mobile and Password Credentials.
c) Click on Login Button.

Expected Result:
a)User is Logged in the Desired Account.
b)User is Redirected to the Home Page.

Pass/Failed Criteria:
a)Pass- User is Logged in the Desired Account and Redirected automatically to the Home Page.
b)Fail- User is not Logged in the Desired Account or any Account and Redirected to the Welcome Page.

6.) Verify Product Search Functionality.
Ans->
Precondition:
a)Product should be registered.

Test Steps:
a) Go to Home Page/Welcome Page.
b) Click on Search Functionality.
c) Search for the Desired Product.

Expected Result:
The Desired Product is Displayed with different Retailers and Pricing.

Pass/Failed Criteria:
a)Pass- Searched or Desired Product is Displayed on Search Page.
b)Fail- Searched or Desired Product is not Displayed on Search Page.
