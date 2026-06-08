# Login Test Cases

| ID     | Test Case            | Steps                                     | Expected Result              |
| ------ | -------------------- | ----------------------------------------- | ---------------------------- |
| TC-001 | Valid Login          | Enter valid username and password         | User accesses dashboard      |
| TC-002 | Invalid Password     | Enter valid username and invalid password | Error message displayed      |
| TC-003 | Invalid Username     | Enter invalid username and valid password | Error message displayed      |
| TC-004 | Empty Username       | Leave username blank                      | Validation message displayed |
| TC-005 | Empty Password       | Leave password blank                      | Validation message displayed |
| TC-006 | Empty Fields         | Leave both fields blank                   | Validation message displayed |
| TC-007 | Logout               | Login and click logout                    | User returns to login page   |
| TC-008 | Password With Spaces | Enter password containing spaces          | Validation message displayed |
| TC-009 | Username With Spaces | Enter username containing spaces          | Validation message displayed |
| TC-010 | Session Persistence  | Refresh page after login                  | Session remains active       |
