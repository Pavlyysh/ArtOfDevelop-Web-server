# rest-api-tutorial

# user-service

# REST API

GET /users -- list of users -- 200, 404, 500
GET /users/:id -- user by id -- 200, 404, 500
POST /users/:id -- create a new user -- 204, 4xx
PUT /users/:id -- fully update the user -- 204/200, 404, 400, 500
PATCH /users/:id -- partially update the user -- 204/200, 404, 400, 500
DELETE /users/:id -- delete the user by id -- 204, 404, 400
 