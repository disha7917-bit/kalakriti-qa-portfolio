# Search Test Cases

| TC ID | Test Scenario | Test Data | Expected Result |
|--------|--------------|------------|----------------|
| SEARCH_001 | Search with valid product name | Handmade Vase | Matching products displayed |
| SEARCH_002 | Search with partial product name | Vase | Relevant products displayed |
| SEARCH_003 | Search with uppercase text | VASE | Results displayed |
| SEARCH_004 | Search with lowercase text | vase | Results displayed |
| SEARCH_005 | Search with mixed case | VaSe | Results displayed |
| SEARCH_006 | Empty search | Blank | Validation or all products |
| SEARCH_007 | Search non-existing product | xyz123 | No products found |
| SEARCH_008 | Search with spaces only | " " | Validation displayed |
| SEARCH_009 | Leading spaces | " vase" | Trimmed correctly |
| SEARCH_010 | Trailing spaces | "vase " | Trimmed correctly |
| SEARCH_011 | Special characters | @#$%^ | Handled properly |
| SEARCH_012 | Numbers only | 12345 | Appropriate response |
| SEARCH_013 | Long search text | 255 chars | Handled without crash |
| SEARCH_014 | Emoji search | 😀 | Handled properly |
| SEARCH_015 | SQL Injection attempt | ' OR 1=1 -- | Blocked |
| SEARCH_016 | XSS attempt | <script>alert(1)</script> | Script blocked |
| SEARCH_017 | Rapid repeated searches | Multiple clicks | Stable behavior |
| SEARCH_018 | Search after page refresh | Valid keyword | Results remain correct |
| SEARCH_019 | Search while offline | Disconnect network | Error message shown |
| SEARCH_020 | Search with tag keyword | Category/tag name | Related products displayed |
