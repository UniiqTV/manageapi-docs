---
layout: default
title: Remove Package
nav_order: 3
parent: Package API
grand_parent: UNIIQ Management API
---

# Remove Package

manage api use to remove package customer from uniiq service

```json
POST https://manageapi.uniiq.id/api/package/disable
Content-Type: application/json
Authorization: Bearer {{token}}

{
    "custPackageId": "(your customer package id)"
}
```

**Response** :
```json
{
    "id": "09041c3c-c847-4d60-8be0-8b9079f83966",
    "message": "Remove Package Success",
    "status": 200
}
```
- *id* : this is customer package id
- *message* : message for response status
- *status* : response status for the request
