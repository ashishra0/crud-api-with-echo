### Echo CRUD API example

### Getting started
* Clone the repo
* Run main.go

#### Usage
* Create a user
```
curl -X POST \
  -H 'Content-Type: application/json' \
  -d '{"name":"John Doe"}' \
  localhost:8080/users
```
* Get user
```
curl localhost:8080/users/1
```
* Update a user
```
curl -X PUT \
  -H 'Content-Type: application/json' \
  -d '{"name":"John"}' \
  localhost:8080/users/1
```
* Delete a user
```
curl -X DELETE localhost:1323/users/1
```