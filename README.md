# Express-API
CRUD with Express JS
## GET
### Get All Data
#### URL
http://localhost:3000/api/posts
#### Output
```json
{
    "status": true,
    "message": "List Data Posts",
    "data": [
        {
            "id": 4,
            "title": "Acome",
            "content": "Bluetooth Sound"
        },
        {
            "id": 3,
            "title": "Milku",
            "content": "Cheap Milk"
        },
        {
            "id": 1,
            "title": "Fantech",
            "content": "Headphone"
        }
    ]
}
```
### Get Data by ID
#### URL
http://localhost:3000/api/posts/0
#### Output
```json
{
    "status": true,
    "message": "Detail Data Post",
    "data": {
        "id": 0,
        "title": "Milku",
        "content": "Cheap of Milk"
    }
}
```
## POST
### Add Data to Database
#### URL
http://localhost:3000/api/posts/store
#### Output
```json
{
    "status": true,
    "message": "Insert Data Successfully"
}
```
## PATCH
### Update Data from Database
#### URL
http://localhost:3000/api/posts/update/2
#### Output
```json
{
    "status": true,
    "message": "Update Data Successfully!"
}
```
## DELETE
### Delete Data from Database
#### Output
http://localhost:3000/api/posts/delete/3
#### Output
```json
{
    "status": true,
    "message": "Delete Data Successfully!"
}
```
