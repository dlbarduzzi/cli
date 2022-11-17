# openssl

```sh
# Print a random string
openssl rand -base64 32

# Print a random string with only alphanumeric characters
openssl rand -base64 32 | tr -dc 'a-zA-Z0-9'; echo
```
