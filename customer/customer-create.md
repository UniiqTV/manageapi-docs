---
layout: default
title: Create New Customer
nav_order: 4
parent: Customer API
grand_parent: UNIIQ Management API
---

# Create New Customer

manage api use to create customer from uniiq service by username authentication

```json
GET https://manageapi.uniiq.id/api/customer/new
Authentication : Bearer token
Content-Type: application/json

{
    "name": "(your name)",
    "phone": "(your phone)",
    "email": "(your email)",
    "password": "(your password)",
    "address": "(your address)",
    "customerId": "(your customerId)",
    "identifier": "(your identifier)"
}
```

**Response** :
```json
{
    "id": "f27b2d18-726d-4183-8682-321ec68b8398",
    "message": "Create Customer Success",
    "status": 200
}
```
- *id* : this is customerId after success create new customer
- *message* : description for response status
- *status* : response status for the request
