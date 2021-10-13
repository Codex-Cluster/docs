## project design
### Phase 1 (As of 12th Oct, 2021):  
**Admin - Dashboard**
Functionalities:  
* Add **Category**
    - catId  
    - catName  
    - catDescription  
    - position  
    - status  
    - image 
* Add **SubCategory**
    - subId  
    - subName  
    - subDescriptions  
    - position  
    - status  
    - image  
    - catId 
* Add **Books** 
    - 

Create angular project to add CURD operation on  
* category  
* subcategory  

### Phase 2 (As of 13th Oct, 2021):  
changlelog:  
* Removed Subcategory functionality   
* User roles added - Customer, Admin  
    * **Admin**  
        * Admin has authority to activate/deactivate customer accounts, as well as view orders placed by customers.  
        * Admin adds coupon codes that can be redeemed by the customers to avail discounts on products.  
    * **Customer**  
        * Customer can search for books by its name, author, isbn or category  
        * Can only see books that have their status == "show".  
        * Can add/remove books to/from wishlist.  
        * Can add/remove books to/from cart  
        * Can manage cart - add/remove/modify quantity and so on.
        * Must be logged in to place order.  
        * Can add shipping/billing addresses, which can be reused later  
        * Able to apply discount coupons in payment page.   
* Featured books section - Sponsored/advertised books are displayed  
* New books - displays the latest books.  
* **Category**:  
    - catId  
    - catName  
    - catDescription  
    - position  
    - status  
    - image  
    - createdAt  
&nbsp;&nbsp;Category is to be sorted by position, and only those category that have their status == "show" are to be made visible to customers.  
* Acquired Book schema, **Book**:  
    - BookID  
    - CatID  
    - Title  
    - ISBN  
    - Year  
    - Price  
    - Description  
    - Position  
    - Status  
    - Image  
   
  

