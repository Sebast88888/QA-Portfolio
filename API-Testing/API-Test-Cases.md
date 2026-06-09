# API Test Cases

| ID      | Endpoint    | Method | Expected Result                   |
| ------- | ----------- | ------ | --------------------------------- |
| API-001 | /posts      | GET    | Returns status 200                |
| API-002 | /posts/1    | GET    | Returns post with ID 1            |
| API-003 | /posts/9999 | GET    | Returns empty result or not found |
| API-004 | /posts      | POST   | Creates new resource              |
| API-005 | /posts/1    | PUT    | Updates existing resource         |
| API-006 | /posts/1    | DELETE | Deletes resource successfully     |
| API-007 | /users      | GET    | Returns list of users             |
| API-008 | /comments   | GET    | Returns comments data             |
| API-009 | /albums     | GET    | Returns albums data               |
| API-010 | /todos      | GET    | Returns todo items                |
