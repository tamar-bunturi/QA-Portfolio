# API Testing

This folder contains API testing collections built in Postman.
Each collection includes requests with test scripts that validate
status codes, response structure, data integrity, and response time.

---

## Collections

### 1. JSONPlaceholder API Testing
A REST API testing collection covering all core HTTP methods.

| Method | Endpoint | Description |
|---|---|---|
| GET | /users | Get all users |
| GET | /users/1 | Get single user |
| POST | /users | Create new user |
| PUT | /users/1 | Update existing user |
| DELETE | /users/1 | Delete user |
| GET | /users/9999 | Non-existing user (404) |

**Total Tests:** 22 tests - all passing ✅

### 2. ReqRes API Testing
A more advanced collection covering authentication, request
chaining, and negative testing scenarios.

| Method | Endpoint | Description |
|---|---|---|
| POST | /api/register | Register new user — saves token |
| POST | /api/login | Login user — saves auth token |
| GET | /api/users | Get all users |
| GET | /api/users/2 | Get single user |
| POST | /api/users | Create user — saves user ID |
| PUT | /api/users/{{userId}} | Update user — uses chained ID |
| DELETE | /api/users/{{userId}} | Delete user — uses chained ID |
| POST | /api/register | Missing password — negative test |
| POST | /api/login | Wrong password — negative test |

**Total Tests:** 34 tests - all passing ✅

**Key concepts demonstrated:**
- 🔗 Request chaining — token and ID saved and reused automatically
- 🔐 Authentication testing
- ❌ Negative testing — error handling validation

---

## How to Use
1. Download the `.json` collection file
2. Open Postman
3. Click **Import**
4. Select the downloaded file
5. Run the collection and see all tests pass

---

## Tools
- Postman
- JavaScript (pm.test assertions)
