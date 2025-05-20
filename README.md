# Identity Reconciliation API

This is a REST API that reconciles identity records based on email and phone number. It accepts and returns data in JSON format.

## 🧩 API Endpoint

**Base URL**  
https://identity-reconciliation-production-4606.up.railway.app/identify


## 📨 Request

- **Method**: `POST`
- **Content-Type**: `application/json`
- **Body**:

```json
{
  "email": "johndoe@example.com",
  "phone": "9876543210"
}
