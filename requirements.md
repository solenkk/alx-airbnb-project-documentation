# 📝 Backend Requirement Specifications – Airbnb Clone

This document outlines the functional and technical specifications for three core backend features: User Authentication, Property Management, and the Booking System.

---

## 1. 🔐 User Authentication

### ✅ Description
Allow users to register and log in securely using email and password. Supports guests and hosts.

### 📌 API Endpoints

#### `POST /api/register`
- **Input:**
  ```json
  {
    "first_name": "John",
    "last_name": "Doe",
    "email": "john@example.com",
    "password": "secret123"
  }
