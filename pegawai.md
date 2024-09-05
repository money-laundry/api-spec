# Auth Spec
BASE URL : api/v1/pegawai

## create

Endpoint : POST pegawai/:idCabang

Request Body :
```json
{
  "email": "johndoe@gmail.com",
  "password": "Azki1234",
  "nama":"string",
  "alamat":"string",
  "nik":"string",
  "no_hp":"string",
  "tempat_lahir":"string",
}
```

Response Body Success :

```json
{
  "status_code": 200,
  "message": "berhasil",
  "data":[
    {
      "pegawaiId":"1",
      "idToko":"1"
    }
  ]
}
```



