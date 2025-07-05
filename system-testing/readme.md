SYSTEM TESTING TEST CASES(Amazon.com)

*Verify Login

1)Test Scenario:
 Verify successful login with valid credentials

2)	Preconditions:
a)	User must be registered with a valid email and password
b)	Application server is running

3)	Test Steps
a)	Open the Browser and go to www.amazon.com.
b)	User will be redirected to the Welcome Page.
c)	User will click on Sign in Button.
d)	User will be Redirected to the Sign in Page.
e)	User will Enter the Valid Mobile Number/E-mail which is registered.
f)	User will Enter the Valid Password.
g)	User will click on Sign in Option.
h)	Confirmation Message is Displayed.

4)	Test Data
a)	E-mail- testuser@gmail.com
b)	Password- Test@432

5)Expected Result
After Entering the Valid Credentials in the Sign in Page then User will be Redirected to the Home Page/Dashboard Page.

6)Actual Result
As Expected.

7)Status
Passed

*Verify product
1)   Test Scenario: 
Verify product search functionality.

2)	Preconditions:
a)	Product must be available in database.
b)	User is on the Home Page.
3)	Test Steps
a)	Open the Browser and go to www.amazon.com.
b)	User will be redirected to the Welcome Page.
c)	User will click on Sign in Button.
d)	User will be Redirected to the Sign in Page.
e)	User will Enter the Valid Mobile Number/E-mail which is registered.
f)	User will Enter the Valid Password.
g)	User will click on Sign in Option.
h)	User will be redirected to the Home Page.
i)	User will click on Search bar and Enter the Product Name and click on the search icon.
j)	User will be redirected to Products Page.

4)	Test Data
a)	E-mail- testuser@gmail.com
b)	Password- Test@432
c)	Product Name- “Phone Cover”

5)Expected Result
After Entering the Valid Product Name in the Search Bar Option then User will be Redirected to the Products Page and Desired product is shown with multiple pricing options.

6)Actual Result
As Expected.

7)Status
Passed


*Verify Cart
1)Test Scenario: 
Verify Adding a Product to Cart.

2)	Preconditions:
a.	Product is in stock
b.	User is Logged in.
c.	User is on Product detail Page.
3)	Test Steps
a.	Open the Browser and go to www.amazon.com.
b.	User will be redirected to the Welcome Page.
c.	User will click on Sign in Button.
d.	User will be Redirected to the Sign in Page.
e.	User will Enter the Valid Mobile Number/E-mail which is registered.
f.	User will Enter the Valid Password.
g.	User will click on Sign in Option.
h.	User will be redirected to the Home Page.
i.	User will click on Search bar and Enter the Product Name and click on the search icon.
j.	User will be redirected Products Page.
k.	User will click on the desired Product.
l.	User will be Redirected to Product Detail Page.
m.	User can choose the Desired Quantity, Variation(if applicable).
n.	User will Click on Add to Cart Functionality.
o.	User will be Redirected to the Cart page.
p.	Confirmation Message will be displayed.

4)	Test Data
a.	E-mail- testuser@gmail.com
b.	Password- Test@432
c.	Product Name- “Phone Cover”
d.	Product Detail- “Spigen Tough Armor Back Cover Case”
e.	Product Quantity- 1
f.	Product Variant- “Black”

5)Expected Result
After Adding the Desired Product from the Product Detail Page along with its Quantity and Variant, the Product should be added to the Cart Page with Selected Product Quantity and Variant with Correct Pricing.

6)Actual Result
As Expected.

7)Status
Passed

*Verify Successful Order
1)   Test Scenario: 
Verify successful order placement.

2)	Preconditions:
a.	User is Logged in.
b.	Cart contains at least 1 Product.
c.	Delivery Address and Payment are set.

3)	Test Steps
a.	Open the Browser and go to www.amazon.com.
b.	User will be redirected to the Welcome Page.
c.	User will click on Sign in Button.
d.	User will be Redirected to the Sign in Page.
e.	User will Enter the Valid Mobile Number/E-mail which is registered.
f.	User will Enter the Valid Password.
g.	User will click on Sign in Option.
h.	User will be redirected to the Home Page.
i.	User will click on Search bar and Enter the Product Name and click on the search icon.
j.	User will be redirected Products Page.
k.	User will click on the desired Product.
l.	User will be Redirected to Product Detail Page.
m.	User can choose the Desired Quantity, Variation (if applicable).
n.	User will Click on Add to Cart Functionality.
o.	User will be Redirected to the Cart page.
p.	Click on Checkout Button.
q.	Enter Address and Payment Method.
r.	After Entering all the Details Click on Checkout Button.
s.	“Order Placed successfully” Confirmation Message is displayed.

4)	Test Data
a.	E-mail- testuser@gmail.com
b.	Password- Test@432
c.	Product Name- “Phone Cover”
d.	Product Detail- “Spigen Tough Armor Back Cover Case”
e.	Product Quantity- 1
f.	Product Variant- “Black”

5)Expected Result
The Product should be added to the Cart Page with Selected Product Quantity and Variant with Correct Pricing and Product and after Checking out the Order should be Placed.

6)Actual Result
As Expected.

7)Status
Passed

*Verify Logout
1)   Test Scenario: Verify logout functionality.

2)	Preconditions:
a.	User is Logged in.
b.	User is on any Authenticated Page.
3)	Test Steps
a.	Open the Browser and go to www.amazon.com.
b.	User will be redirected to the Welcome Page.
c.	User will click on Sign in Button.
d.	User will be Redirected to the Sign in Page.
e.	User will Enter the Valid Mobile Number/E-mail which is registered.
f.	User will Enter the Valid Password.
g.	User will click on Sign in Option.
h.	User will be redirected to the Home Page.
i.	User will click on Search bar and Enter the Product Name and click on the search icon.
j.	User will be redirected Products Page.
k.	User will click on the desired Product.
l.	User will be Redirected to Product Detail Page.
m.	User can choose the Desired Quantity, Variation (if applicable).
n.	User will Click on Add to Cart Functionality.
o.	User will be Redirected to the Cart page.
p.	Click on Profile Button.
q.	Click on Logout Button.
r.	“User Logged out Successfully” Confirmation message is Displayed.
4)	Test Data
a.	E-mail- testuser@gmail.com
b.	Password- Test@432
c.	Product Name- “Phone Cover”
d.	Product Detail- “Spigen Tough Armor Back Cover Case”
e.	Product Quantity- 1
f.	Product Variant- “Black”

5)Expected Result
The Product should be added to the Cart Page with Selected Product Quantity and Variant with Correct Pricing and Product and after clicking on Logout User should be Logged out.

6)Actual Result
As Expected.

7)Status
Passed

