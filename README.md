# Coupon Inventory System
 
This project is a coupon inventory system. It allows the user to view the coupons file, add new coupons (manually or from a file) or search for specific coupons. 

Classes included in this project and their methods: 

1. CIS class:
main– responsible for running the project, includes both the initial and main menu of the application, readCoupons – responsible for reading the file to the ArrayList of Coupon objects, addCoupons – allows the user to append the ArrayList with a manually input coupon, searchCoupons – allows the user to search for a coupon by its fields, sortAndDisplay – allows the user to view the coupons SORTED by its fields

2. Coupon class: getProduct – returns the product’s name, getPrice – returns the product’s initial price, getProvider – returns the coupon’s provider, getDiscountRate – returns the discount rate, e.g. 20, 30..., getExpiration – returns the expiration in # of days, getStatus – returns the status (Unused/Redeemed), getFinalPrice – returns the final price after the discount rate, @Override toString – overrides the default object printing method