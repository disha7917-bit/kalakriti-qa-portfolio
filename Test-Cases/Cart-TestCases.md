# Cart Test Cases

| TC ID | Test Scenario | Expected Result |
|--------|--------------|----------------|
| CART_001 | Add product to cart | Product added |
| CART_002 | Add same product twice | Quantity updated |
| CART_003 | Remove product | Product removed |
| CART_004 | Update quantity | Quantity updated |
| CART_005 | Quantity = 0 | Validation shown |
| CART_006 | Negative quantity | Validation shown |
| CART_007 | Add out-of-stock product | Not allowed |
| CART_008 | Empty cart checkout | Validation displayed |
| CART_009 | Cart persistence after refresh | Cart retained |
| CART_010 | Cart persistence after login | Cart retained |
| CART_011 | Multiple products added | Correct totals |
| CART_012 | Remove last product | Cart becomes empty |
| CART_013 | Cart total calculation | Accurate total |
| CART_014 | Rapid add-to-cart clicks | No duplicates |
| CART_015 | Browser refresh | Cart maintained |
| CART_016 | Logout and login | Cart behavior verified |
| CART_017 | Network interruption | Proper error |
| CART_018 | Special product variants | Correct cart item |
| CART_019 | Large quantity value | Validation handled |
| CART_020 | Cart icon count | Matches cart quantity |
