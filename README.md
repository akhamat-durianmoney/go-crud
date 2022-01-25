How to run local
- go ran main.go


all route
// Login Route
localhost:8080/login POST

//Users routes
- localhost:8080/users  GET => to get all user
- localhost:8080/users/1 GET => to get specific user
- localhost:8080/users POST => to create new user
- localhost:8080/users/1 PUT => to edit spesific user
- localhost:8080/users/1 DELETE => to delete spesific user

```
payload for login
{
    "email": "admin@admin.com",
    "password": "password"
}
```

```
payload for create and update
{
    "nickname": "admina",
    "email": "admin1@admin.com",
    "password": "admina"
}
```

for users endpoind using JWT auth
