# Registration Test Cases

| TC ID | Test Scenario | Test Steps | Test Data | Expected Result |
|--------|--------------|------------|-----------|----------------|
| REG_001 | Register with valid details | Fill all fields correctly | Valid data | Registration successful |
| REG_002 | Empty name | Leave name blank | Valid email/password | Name required message |
| REG_003 | Empty email | Leave email blank | Other fields valid | Email required message |
| REG_004 | Empty password | Leave password blank | Other fields valid | Password required message |
| REG_005 | Empty confirm password | Leave confirm password blank | Other fields valid | Validation displayed |
| REG_006 | Invalid email format | Enter invalid email | abc.com | Email validation shown |
| REG_007 | Password mismatch | Different passwords | Password != Confirm Password | Error displayed |
| REG_008 | Duplicate email | Existing email | Registered email | User already exists |
| REG_009 | Password below minimum length | Short password | 3 chars | Validation displayed |
| REG_010 | Password at minimum length | Valid minimum length | 8 chars | Accepted |
| REG_011 | Maximum name length | Long name | 255 chars | Processed correctly |
| REG_012 | Name with numbers | John123 | Mixed input | Validation or acceptance |
| REG_013 | Name with special characters | @John# | Special chars | Validation handled |
| REG_014 | Leading spaces in name | " John" | Spaces | Trimmed or validation |
| REG_015 | Trailing spaces in name | "John " | Spaces | Trimmed or validation |
| REG_016 | SQL Injection attempt | Registration form | ' OR 1=1 -- | Blocked |
| REG_017 | XSS attempt | Name field | <script>alert(1)</script> | Script blocked |
| REG_018 | Multiple rapid submissions | Double-click Register | Valid data | Single account created |
| REG_019 | Refresh after registration | Register then refresh | Valid user | No duplicate account |
| REG_020 | Network interruption | Disconnect internet during submit | Valid data | Proper error message |
