# Login Test Cases

| TC ID | Test Scenario | Test Steps | Test Data | Expected Result |
|--------|--------------|------------|-----------|----------------|
| LOGIN_001 | Login with valid credentials | Enter valid email and password | Valid credentials | Login successful |
| LOGIN_002 | Empty email | Leave email blank | Password entered | Email required message |
| LOGIN_003 | Empty password | Leave password blank | Email entered | Password required message |
| LOGIN_004 | Empty email and password | Leave both fields blank | None | Validation messages displayed |
| LOGIN_005 | Invalid email format | Enter invalid email | abc.com | Email validation shown |
| LOGIN_006 | Wrong password | Enter wrong password | Valid email + wrong password | Invalid credentials |
| LOGIN_007 | Non-registered email | Enter unknown email | Fake email | User not found |
| LOGIN_008 | Leading spaces in email | Add spaces before email | " test@gmail.com" | Trimmed or validation |
| LOGIN_009 | Trailing spaces in email | Add spaces after email | "test@gmail.com " | Trimmed or validation |
| LOGIN_010 | Password case sensitivity | Change password case | PASSWORD123 | Login denied |
| LOGIN_011 | Email case sensitivity | Change email case | TEST@MAIL.COM | Handled correctly |
| LOGIN_012 | Maximum email length | Enter long email | 255 chars | Processed correctly |
| LOGIN_013 | Very long password | Enter 100 char password | Long string | Validation handled |
| LOGIN_014 | SQL Injection attempt | Enter SQL payload | ' OR 1=1 -- | Access denied |
| LOGIN_015 | XSS attempt | Enter script | <script>alert(1)</script> | Script blocked |
| LOGIN_016 | Double click login button | Rapid click | Valid credentials | Single request processed |
| LOGIN_017 | Refresh after login | Refresh browser | Logged in user | Session maintained |
| LOGIN_018 | Back button after logout | Logout then back | Browser back | User remains logged out |
| LOGIN_019 | Network interruption | Disconnect internet | Login attempt | Proper error message |
| LOGIN_020 | Session timeout | Wait for timeout | Logged in session | Redirect to login |
