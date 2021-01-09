# Coupon Inventory System
 
This project is a coupon inventory system. It allows the user to view the coupons file, add new coupons (manually or from a file) or search for specific coupons. 

Classes included in this project and their methods: 

1. CIS class:
   a. main– responsible for running the project, includes both the initial and main menu of the application, readCoupons – responsible for reading the file to the ArrayList of Coupon objects, addCoupons – allows the user to append the ArrayList with a manually input coupon, searchCoupons – allows the user to search for a coupon by its fields, sortAndDisplay – allows the user to view the coupons SORTED by its fields

2. Coupon class:
	a. getProduct – returns the product’s name
	b. getPrice – returns the product’s initial price
	c. getProvider – returns the coupon’s provider
	d. getDiscountRate – returns the discount rate, e.g. 20, 30...
	e. getExpiration – returns the expiration in # of days
	f. getStatus – returns the status (Unused/Redeemed)
	g. getFinalPrice – returns the final price after the discount rate
	h. @Override toString – overrides the default object printing method