---
layout: default
title: Authentication
nav_order: 1
parent: UNIIQ Management API
---

## Authentication

manage api use bearer token authentication, to get bearer token authentication you need to use your login and password that registered to uniiq service

```json
POST http://manageapi.uniiq.id/auth
Content-Type: application/json

{
"username": "(your content-provider / service-provider username)",
"password": "(your content-provider / service-provider password)"
}
```

**Response** :
```json
{
  "access_token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzUxMiJ9.asdfasdfasdfasdfasdf.-FSZGEFpHow33QWGINoAeEDt_YB-asdfasdfasdfasdfasdfasdf",
  "userdetail": {
    "id": "12d12wd21wd-12d12wd-45cc-qsdqwd-asdfasdfasdf",
    "email": "",
    "enabled": true,
    "status": "Active"
  },
  "status": "0001",
  "message": "OK"
}
```
- *access_token* : Access token is a standard jwt format, this token needed to access api functions
- *userdetail* : userdetail object, user that registered in uniiq service
	- *id*  : user database id
	- email : user registered email
	- enabled: user status
	- status : status user in database
- *status* : response status for the request
- *message* : description for response status