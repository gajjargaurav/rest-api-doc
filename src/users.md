## User Collection [/users]

### List All Users [GET]

+ Response 200 (application/json; charset=utf-8)
    + Attributes (array[User Response])

### Signup [POST]

Create new user by posting a JSON object

+ Request (application/json; charset=utf-8)
    + Attributes (User Request)

+ Response 201 (application/json; charset=utf-8)
    + Headers

            Location: /users/userid
    + Attributes (User Response)
