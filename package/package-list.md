---
layout: default
title: Package List
nav_order: 1
parent: Package API
grand_parent: UNIIQ Management API
---

# Package List

manage api use to get package-list from uniiq service by username authentication

```
GET https://manageapi.uniiq.id/api/package/list
Authorization: Bearer {{token}}
```

**Response** :
```json
[
    {
        "id": "3e0996bb-cb41-4475-baed-b4b4707225c7",
        "name": "TestDev",
        "idString": "TestDev",
        "contentProvider": {
            "id": "833770c3-a9ac-4019-8233-c25767769e40",
            "name": "KINGS",
            "epgUrl": null
        },
        "serviceMulticast": true,
        "serviceOtt": true,
        "serviceMobileapp": false,
        "color": "",
        "promoPackage": "",
        "adult": false,
        "qualityLow": true,
        "qualityMedium": true,
        "qualityHigh": true,
        "country": "ID"
    },
    {
        "id": "c48f1201-8330-476b-9bab-8688d61e507b",
        "name": "PAKET 40 CH",
        "idString": "",
        "contentProvider": {
            "id": "833770c3-a9ac-4019-8233-c25767769e40",
            "name": "KINGS",
            "epgUrl": null
        },
        "serviceMulticast": true,
        "serviceOtt": true,
        "serviceMobileapp": false,
        "color": "#e31111",
        "promoPackage": "",
        "adult": false,
        "qualityLow": true,
        "qualityMedium": true,
        "qualityHigh": true,
        "country": "ID"
    },
    {
        "id": "d2093307-7bfa-432a-b231-a3620ba2bd09",
        "name": "test2channel",
        "idString": "",
        "contentProvider": {
            "id": "833770c3-a9ac-4019-8233-c25767769e40",
            "name": "KINGS",
            "epgUrl": null
        },
        "serviceMulticast": true,
        "serviceOtt": true,
        "serviceMobileapp": true,
        "color": "#d22323",
        "promoPackage": "",
        "adult": false,
        "qualityLow": true,
        "qualityMedium": true,
        "qualityHigh": true,
        "country": ""
    }
]
```
- *id* : this is package id
- *name* : this is name
- *idString* : this is idString
- *contentProvider id* : this is content provider id
- *contentProvider name* : this is content provider name
- *contentProvider epgUrl* : this is content provider epgUrl
- *serviceMulticast* : this is status for the serviceMulticast
- *serviceOtt* : this is status for the serviceOtt
- *serviceMobileapp* : this is status for the serviceMobileapp
- *color* : this is color for the selected
- *promoPackage* : this is promo package for the selected
- *adult* : this is status for the adult
- *qualityLow* : this is status for the qualityLow
- *qualityMedium* : this is status for the qualityMedium
- *qualityHigh* : this is status for the qualityHigh
- *country* : this is ID from country