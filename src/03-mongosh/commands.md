## Conect to container

```sh
docker-compose exec mongodb bash
```
## Conect with mongosh

```sh
mongosh "mongodb://localhost:27017/"
```

```sh
show dbs
show collections
```

```sh
use("test")
db.products.find()
```
