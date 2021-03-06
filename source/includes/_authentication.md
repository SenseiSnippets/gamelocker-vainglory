# Authorization

> To specify the API key, use this code:

```shell
# With shell, you can just pass the correct header with each request
curl "https://api.dc01.gamelockerapp.com" \
  -H "Authorization: xxx.yyy.zzz"
```
```python
```

```go
```

```javascript
```

> Make sure to replace `xxx.yyy.zzz` with your API key.

We require a JSON Web Token ([JWT](https://jwt.io/)) be sent along with your request via the `Authorization` header.  
JWTs are passed as bearer tokens in the Authorization header, and look like the following:

`Authorization: <Enter your API Key>`


There's no need to create JWTs manually, they will be created for you when you register for the API.
For now anything is accepted.

In some cases an `X-API-KEY` will give you more access to information, and in all
 cases it means that you are operating under a per-token rate limit.

<aside class="notice">
Get ready!  Soon you'll be able to register your app and get a shiny new API key using our developer portal.
</aside>
