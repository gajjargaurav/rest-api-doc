## User [/users/{user_id}]

+ Parameters
    + user_id: userid (required, string)

### View profile [GET]

+ Response 200 (application/json; charset=utf-8)
    + Attributes (User Response)

### Update a profile [PATCH]

+ Request (application/json; charset=utf-8)
    + Attributes (User Base)
        * firstName: Jane

+ Response 200 (application/json; charset=utf-8)
    + Attributes (User Response)
        * firstName: Jane

### Delete a user [DELETE]

+ Response 204
