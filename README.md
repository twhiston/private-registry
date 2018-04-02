# Private Registry

You need to add an auth/nginx.htpasswd file

```
docker run --rm --entrypoint htpasswd registry:2 -Bbn my_user my_pass > auth/nginx.htpasswd
```
