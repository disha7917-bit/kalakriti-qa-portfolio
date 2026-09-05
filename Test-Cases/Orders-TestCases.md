# Orders Test Cases

| TC ID | Test Scenario | Expected Result |
|--------|--------------|----------------|
| ORDER_001 | View order history | Orders displayed |
| ORDER_002 | View order details | Details displayed |
| ORDER_003 | Newly placed order visible | Order listed |
| ORDER_004 | Order total accuracy | Correct amount |
| ORDER_005 | Multiple orders | All displayed |
| ORDER_006 | Empty order history | Message shown |
| ORDER_007 | Refresh order page | Data retained |
| ORDER_008 | Access orders without login | Redirect to login |
| ORDER_009 | Invalid order ID | Error handled |
| ORDER_010 | Large order history | Performance acceptable |
| ORDER_011 | Search order | Matching result |
| ORDER_012 | Filter orders | Correct filtering |
| ORDER_013 | Cancel order (if available) | Order cancelled |
| ORDER_014 | Order status update | Correct status |
| ORDER_015 | Network interruption | Error handled |
| ORDER_016 | Session timeout | Redirect to login |
| ORDER_017 | Browser back after logout | No access |
| ORDER_018 | Duplicate order prevention | Single order only |
| ORDER_019 | Order data consistency | Correct data |
| ORDER_020 | Download invoice (if available) | Invoice downloaded |
