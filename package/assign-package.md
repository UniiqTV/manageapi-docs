---
layout: default
title: Assign Package To User
nav_order: 2
parent: Package API
grand_parent: UNIIQ Management API
---

# Assign Package

manage api use to Assign new package to customer from uniiq service

```json
POST https://manageapi.uniiq.id/api/package/new
Content-Type: application/json
Authorization: Bearer {{token}}

{
    "idCust": "(your customer id)",
    "packageData":[
        {
            "package_id": "(your package id)",
            "expired_date": "(your expired date)",
            "unlimited": true
        }
    ]
}
```

**Response** :
```json
{
    "custpackageid": "16114ed5-f6a8-4904-b820-a193cb86e6fa",
    "message": "add package success",
    "status": 200
}
```
- *id* : this is customer package id
- *message* : message for response status
- *status* : response status for the request
