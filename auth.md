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
  "message": "otp berhasil dikirim silahkan cek email anda",
  "data":[
    {
      "userId":"1",
      "role":"pegawai/owner"
    }
  ]
}
```

Endpoint : POST /register

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
  "message": "otp berhasil dikirim silahkan cek email anda",
  "data":[
    {
      "userId":"1",
      "role":"owenr",
      "idToko":"1"
    }
  ]
}
```






