# Getting Started

This documentation contains examples for interacting with the AdminHot API.

## Authentication

Most endpoints require authentication via a bearer token. Retrieve your personal access token from your profile or via the login endpoints. Send the token in the `Authorization` header with the `Bearer` scheme:

```
Authorization: Bearer YOUR_TOKEN_HERE
```

Requests missing or using an invalid token will receive `401 Unauthorized`.
