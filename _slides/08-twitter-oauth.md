---
transition: zoom
---

## Example: Twitter

- [Step 1: Initiate a Request for our app with Twitter](https://developer.twitter.com/en/docs/authentication/api-reference/request_token): `POST https://api.twitter.com/oauth/request_token`

Header:
```
OAuth oauth_nonce="K7ny27JTpKVsTgdyLdDfmQQWVLERj2zAK5BslRsqyw", oauth_callback="http%3A%2F%2Fmyapp.com%3A3005%2Ftwitter%2Fprocess_callback", oauth_signature_method="HMAC-SHA1", oauth_timestamp="1300228849", oauth_consumer_key="OqEqJeafRSF11jBMStrZz", oauth_signature="Pc%2BMLdv028fxCErFyi8KXFM%2BddU%3D", oauth_version="1.0"
```

- Response is passed to the server <code>oauth_callback</code> as an <code>oauth_token</code>

```
oauth_token=Z6eEdO8MOmk394WozF5oKyuAv855l4Mlqo7hhlSLik&oauth_token_secret=Kd75W4OQfb2oJTV0vzGzeXftVAwgMnEK9MumzYcM&oauth_callback_confirmed=true
```