---
layout: default
title: Disable Package
nav_order: 3
parent: Package API
grand_parent: UNIIQ Management API
---

# Disable Package

manage api use to disable package customer from uniiq service

```json
POST https://manageapi.uniiq.id/api/package/disable
Content-Type: application/json
Authorization: Bearer {{token}}

{
    "idCust": "(your customer id)",
    "custPackageId": "(your customer package id)"
}
```

**Response** :
```json
{
    "id": "04846af9-1c13-48ae-997e-a54fc4fe1129",
    "message": "Disable Package Success",
    "status": 200
}
```
- *id* : this is customer package id
- *message* : message for response status
- *status* : response status for the request
