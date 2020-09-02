---
transition: zoom
---

## Example: Twitter

- [Application-only Bearer Token](https://developer.twitter.com/en/docs/authentication/oauth-2-0/application-only)
- [Obtaining a Token](https://developer.twitter.com/en/docs/authentication/api-reference/token)
- `POST https://api.twitter.com/oauth2/token`
  - Header: `Authorization Basic <INPUT>`
  - Header: `application/x-www-form-urlencoded;charset=UTF-8`
  
- Body: `grant_type=client_credentials`