To send JSON data using cURL with headers and authentication, you can use the following command:

```sh
curl -X POST https://api.example.com/resource \
     -H "Content-Type: application/json" \
     -H "Authorization: Bearer YOUR_ACCESS_TOKEN" \
     -d '{"key1":"value1", "key2":"value2"}'
```

Here's a breakdown of the command:

- `-X POST`: Specifies the HTTP method to use (POST in this case).
- `https://api.example.com/resource`: The URL of the API endpoint.
- `-H "Content-Type: application/json"`: Sets the `Content-Type` header to `application/json` to indicate that the request body contains JSON data.
- `-H "Authorization: Bearer YOUR_ACCESS_TOKEN"`: Sets the `Authorization` header with a bearer token for authentication.
- `-d '{"key1":"value1", "key2":"value2"}'`: Specifies the JSON data to send in the request body.

Replace `https://api.example.com/resource` with the actual URL of the API endpoint, `YOUR_ACCESS_TOKEN` with your actual access token, and the JSON data with the data you want to send.
