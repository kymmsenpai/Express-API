# Express-API
CRUD with Express JS
## GET
### Get All Data
#### URL
http://localhost:3000/api/posts
#### Output
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
### Get Data by ID
http://localhost:3000/api/posts/0
## POST
### Add Data to Database
http://localhost:3000/api/posts/store
## PATCH
### Update Data from Database
http://localhost:3000/api/posts/update/2
## DELETE
### Delete Data from Database
http://localhost:3000/api/posts/delete/3
