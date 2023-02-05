
## Authentication
manage api use bearer token authentication, to get bearer token authentication you need to use your login and password that registered to uniiq service

```
POST http://manageapi.uniiq.id/auth
Content-Type: application/json

{
  "username": "(your content-provider / service provider username)",
  "password": "(your content-provider / service provider password)"
}
```
