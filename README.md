Symfony api skeleton
====

routes enabled:</br>
-post /oauth/v2/token</br>
-post /users</br>
-get /users</br>
-get /users/{id}

====

First you need to create a user and a client

```javascript

bin/console fos:user:create

```

Then insert a client in your database

```javascript

INSERT INTO `oauth2_clients` VALUES (NULL, '3bcbxd9e24g0gk4swg0kwgcwg4o8k8g4g888kwc44gcc0gwwk4', 'a:0:{}', '4ok2x70rlfokc8g0wws8c8kwcokw80k44sg48goc0ok4w0so0k', 'a:1:{i:0;s:8:"password";}');

```

====

I recommand to use Postman to test your api

get a Token:

![get a token]
(http://hpics.li/4ce29bb)

![register a user]
(http://hpics.li/9d044b4)

**Documentation:**

[https://gist.github.com/tjamps/11d617a4b318d65ca583]
(https://gist.github.com/tjamps/11d617a4b318d65ca583)
[https://bitgandtter.wordpress.com/2015/09/03/symfony-a-restful-app-motivation/]
(https://bitgandtter.wordpress.com/2015/09/03/symfony-a-restful-app-motivation/)