Symfony api skeleton
====

routes enabled:
post /oauth/v2/token
post /users
get /users
get /users/{id}

====

first you need to create a user and a client

```javascript

bin/console fos:user:create

```

then insert a client in your database

```javascript

INSERT INTO `oauth2_clients` VALUES (NULL, '3bcbxd9e24g0gk4swg0kwgcwg4o8k8g4g888kwc44gcc0gwwk4', 'a:0:{}', '4ok2x70rlfokc8g0wws8c8kwcokw80k44sg48goc0ok4w0so0k', 'a:1:{i:0;s:8:"password";}');

```