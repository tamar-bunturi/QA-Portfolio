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

**Total Tests:** 22 tests — all passing ✅

### 2. ReqRes API Testing
Coming soon 🔜

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
