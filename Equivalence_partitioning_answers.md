Task 1: 

| Input Field | Valid Equivalence Classes | Invalid Equivalence Classes |
|-------------|---------------------------|-----------------------------|
| Age         | 18 to 120                 | < 18                        |
|             |                           | > 120                       |
|             |                           | Invalid input               |

Task 2:

| Input Field | Valid Equivalence Classes        | Invalid Equivalence Classes |
|-------------|----------------------------------|-----------------------------|
| Email       | contain valid email formatting   | Invalid characters          |
|             | (example blah@domainname.com)    | Missing domain address      |
|             |                                  | Missing the @ symbol        |


Task 3: 

| Input Field | Valid Equivalence Classes                  | Invalid Equivalence Classes |
|-------------|--------------------------------------------|-----------------------------|
| Password    | - between and including 8 to 20 characters | - under 8 characters        |
|             | - min of 1 uppercase letter                | - no uppercase letter       |
|             | - min of 1 lowercase letter                | - no lowercase letter       |
|             | - min of 1 digit used                      | - no digit                  |