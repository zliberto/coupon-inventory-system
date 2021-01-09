# Coupon Inventory System
 
This project is a coupon inventory system. It allows the user to view the coupons file, add new coupons (manually or from a file) or search for specific coupons. 

Classes included in this project and their methods: 

1. CIS class:
	a. main– responsible for running the project, includes both the initial and main menu of the application.
	b. readCoupons – responsible for reading the file to the ArrayList of Coupon objects
	c. addCoupons – allows the user to append the ArrayList with a manually input coupon
	d. searchCoupons – allows the user to search for a coupon by its fields:
		1. Product name 
		2. Price
		3. Provider
		4. Discount Rate
		5. Expiration 
		6. Status
		7. Final Price
	e. sortAndDisplay – allows the user to view the coupons SORTED by either:
		1. Product name 
		2. Price
		3. Provider
		4. Discount Rate
		5. Expiration 
		6. Status
		7. Final Price

2. Coupon class:
	a. getProduct – returns the product’s name
	b. getPrice – returns the product’s initial price
	c. getProvider – returns the coupon’s provider
	d. getDiscountRate – returns the discount rate, e.g. 20, 30...
	e. getExpiration – returns the expiration in # of days
	f. getStatus – returns the status (Unused/Redeemed)
	g. getFinalPrice – returns the final price after the discount rate
	h. @Override toString – overrides the default object printing method