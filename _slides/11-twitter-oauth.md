---
transition: zoom
---

## Example: Twitter

- [Use the key as follows](https://developer.twitter.com/en/docs/twitter-api/v1/tweets/post-and-engage/api-reference/post-statuses-update): 

```
curl -XPOST 
  --url 'https://api.twitter.com/1.1/statuses/update.json?status=hello' 
  --header 'authorization: OAuth
  oauth_consumer_key="oauth_customer_key",
  oauth_nonce="generated_oauth_nonce",
  oauth_signature="generated_oauth_signature",
  oauth_signature_method="HMAC-SHA1",
  oauth_timestamp="generated_timestamp",
  oauth_token="oauth_token",
  oauth_version="1.0"'
```

- How might we use the previous response to facilitate user logins to our application, without requiring a password of our own?