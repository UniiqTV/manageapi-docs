---
layout: default
title: Remove Device
nav_order: 3
parent: Package API
grand_parent: UNIIQ Management API
---

# Remove Device

manage api use to remove device customer from uniiq service

```json
POST https://manageapi.uniiq.id/api/device/remove
Content-Type: application/json
Authorization: Bearer {{token}}

{
    "customerId": "(your customer id)",
    "macAddress": "(your macaddress)"
}
```

**Response** :
```json
{
    "id": "02591673-fb12-4d3a-aa31-782ca7989abe",
    "message": "Remove Device Success",
    "status": 200
}
```
- *id* : this is device id
- *message* : message for response status
- *status* : response status for the request
