FORMAT: 1A

# REST API Specification
Testing out an awesome REST API documentation

## The Basics
The API is designed according to REST principles. All API access is over HTTPS.

The API accepts JSON in request bodies and requires that the `content-type: application/json; charset=utf-8` header be specified for all such requests. The API will always respond with a JSON object. Depending on the context, resources may be returned as single objects or as arrays of objects, nested within the response object.

All timestamps are returned in [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) format.

## HTTP Verbs
Where possible, standard [HTTP Verbs](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#Request_methods) are used for each action.

Verb | Description
--- | ---
GET | Used for retrieving resources
POST | Used for creating resources
PATCH | Used for updating resources with partial JSON data.
DELETE | Used for deleting resources

## Status codes
The API uses standard [HTTP Status Codes](https://github.com/for-GET/know-your-http-well/blob/master/status-codes.md) to communicate the response status.

## Rate Limits
At this stage there is no specified rate limiting mechanism in place. The API would start returning the `429 Too Many Requests` HTTP status code if such limits were to be exceeded.

## Group API Root

This resource offers the initial API capabilities in
the form of the links in the JSON body.

# Group Users
Resources related to users in the API.

:[User Collection](users.md)
:[User Resource](user.md)

# Data Structures
:[Data Structures](struct.md)
