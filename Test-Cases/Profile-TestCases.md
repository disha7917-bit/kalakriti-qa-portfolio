# Profile Test Cases

| TC ID | Test Scenario | Expected Result |
|--------|--------------|----------------|
| PROFILE_001 | View profile | Profile displayed |
| PROFILE_002 | Update name | Name updated |
| PROFILE_003 | Update email | Email updated |
| PROFILE_004 | Invalid email update | Validation shown |
| PROFILE_005 | Empty name update | Validation shown |
| PROFILE_006 | Long name update | Handled correctly |
| PROFILE_007 | Special characters in name | Validation handled |
| PROFILE_008 | Update phone number | Updated successfully |
| PROFILE_009 | Invalid phone number | Validation shown |
| PROFILE_010 | Refresh profile page | Data persists |
| PROFILE_011 | Logout from profile | Logout successful |
| PROFILE_012 | Access profile without login | Redirect to login |
| PROFILE_013 | Update address | Saved successfully |
| PROFILE_014 | Remove address | Removed successfully |
| PROFILE_015 | Multiple updates | Saved correctly |
| PROFILE_016 | Session timeout while editing | Proper handling |
| PROFILE_017 | SQL Injection attempt | Blocked |
| PROFILE_018 | XSS attempt | Blocked |
| PROFILE_019 | Browser back after logout | No access |
| PROFILE_020 | Profile data consistency | Correct data displayed |
