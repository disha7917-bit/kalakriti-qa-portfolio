# Checkout Test Cases

| TC ID | Test Scenario | Expected Result |
|--------|--------------|----------------|
| CHECKOUT_001 | Checkout with valid cart | Order placed successfully |
| CHECKOUT_002 | Checkout with empty cart | Validation displayed |
| CHECKOUT_003 | Missing shipping address | Address required |
| CHECKOUT_004 | Missing phone number | Validation displayed |
| CHECKOUT_005 | Invalid phone number | Validation displayed |
| CHECKOUT_006 | Invalid pincode | Validation displayed |
| CHECKOUT_007 | Long address input | Handled correctly |
| CHECKOUT_008 | Special characters in address | Handled correctly |
| CHECKOUT_009 | Multiple products checkout | Correct total |
| CHECKOUT_010 | Refresh during checkout | Data retained or handled |
| CHECKOUT_011 | Browser back during checkout | No data corruption |
| CHECKOUT_012 | Network interruption | Error message shown |
| CHECKOUT_013 | Double click Place Order | Single order created |
| CHECKOUT_014 | Very large quantity checkout | Validation handled |
| CHECKOUT_015 | Checkout after session timeout | Redirect to login |
| CHECKOUT_016 | Order summary accuracy | Totals correct |
| CHECKOUT_017 | Shipping charge calculation | Correct charge |
| CHECKOUT_018 | Tax calculation | Correct tax |
| CHECKOUT_019 | Out-of-stock item during checkout | Prevent order |
| CHECKOUT_020 | Successful order confirmation | Confirmation displayed |
