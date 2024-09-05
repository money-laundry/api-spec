# Auth Spec
BASE URL : api/v1/auth

## Login

Endpoint : GET /login

Request Body :
```json
{
  "email": "johndoe@gmail.com",
  "password": "Azki1234"
}
```

Response Body Success :

```json
{
  "status_code": 200,
  "message": "berhasil",
  "data":[
    {
      "userId":"1",
      "role":"pegawai/owner"
    }
  ]
}
```

Endpoint : POST /register(khusus owner aja sekalian bikin toko pusat)

Request Body :
```json
{
  "name": "azki",
  "username": "azki",
  "email": "johndoe@gmail.com",
  "password": "Azki1234",
  "brand":"string",
  "alamat":"string",
  "logo": "File"
}
```

Response Body Success :

```json
{
  "status_code": 200,
  "message": "berhasil",
  "data":[
    {
      "userId":"1",
      "idToko":"1"
    }
  ]
}
```






