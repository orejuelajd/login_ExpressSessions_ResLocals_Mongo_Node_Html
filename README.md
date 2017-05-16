# Basic login using ExpressJs Sessions, res.locals, MongoDB, NodeJs and HTML

## In Database (MongoDB)

* Database: test
* Collections: users, registers

### In users:

```
> db.users.insert({"username": "user-a", "password": "123", "role": "user_a"})
> db.users.insert({"username": "user-b", "password": "1234", "role": "user_b"})
```

## To run server:

```
node server.js
```