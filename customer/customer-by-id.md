---
layout: default
title: Customer By ID
nav_order: 2
parent: Customer API
grand_parent: UNIIQ Management API
---

# Customer By ID

manage api use to get customer from uniiq service by id

```
GET https://manageapi.uniiq.id/api/customer?id={id}
Authorization: Bearer {{token}}
```

**Response** :
```json
{
    "id": "b77143a4-eacc-45af-ab8b-667d203ad179",
    "name": "Developer",
    "phone": "11111",
    "email": "dev@kings.id",
    "address": "bekasi",
    "customerId": "12313123"
}
```
- *id* : this is id from customer
- *name* : this is name from customer
- *phone* : this is phone from customer
- *email* : this is email from customer
- *address* : this is address from customer
- *customerId* : this is CustomerId from customer
