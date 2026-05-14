# API Testing Practice

## 📌 Tools
- Postman
- REST API
- JSON

---

# HTTP Methods

| Method | Description |
|---|---|
| GET | Retrieve data |
| POST | Create new data |
| PUT | Update existing data |
| DELETE | Delete data |

---

# Example GET Request

```http
GET /users
```

Expected Status Code:

```text
200 OK
```

---

# Example POST Request

```http
POST /users
```

Request Body:

```json
{
  "name": "John",
  "email": "john@gmail.com"
}
```

Expected Status Code:

```text
201 Created
```

---

# Common Status Codes

| Code | Meaning |
|---|---|
| 200 | Success |
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | Not Found |
| 500 | Server Error |

---

# API Testing Checks

- Verify status code
- Verify response body
- Verify response time
- Verify JSON structure
- Verify error handling
