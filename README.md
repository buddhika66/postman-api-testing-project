# API Testing Project using Postman

## 📌 Project Overview
This project demonstrates API testing using Postman for RESTful services.

## 🛠 Tools Used
- Postman
- REST API
- JavaScript (Postman scripting)

## ✅ Testing Coverage
- Status code validation
- Response body verification
- Negative testing
- Environment variables usage
- Automated test scripts

## 📊 Sample Test Script
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
