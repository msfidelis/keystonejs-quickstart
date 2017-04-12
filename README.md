# keystonejs-quickstart


## Dependências 

### NodeJS
* Link: http://nodejs.org/download/

### MongoDB
* Link: https://www.mongodb.com/download-center#community

### Optional (Docker & Docker-Compose)
> Caso não queira instalar o Mongo localmente
* Link Docker: https://docs.docker.com/engine/installation/
* Link Compose: https://docs.docker.com/compose/install/

> Sem composer
```
$ docker run -v mongo_data:/data/db -p 27017:27017 mongo
```

> Com o composer
```
$ docker-compose up -d
```

### Yeoman - Project Generator
* Link: http://yeoman.io/

```
$ npm install -g yo
```

### Keystone = Project Generator
* Link: https://github.com/keystonejs/generator-keystone

```
$ npm install -g generator-keystone
```

## Gerando o Esqueleto e o Helper inicial 

```
$ mkdir fidelis
$ cd fidelis
$ yo keystone
```

![Start](http://i.imgur.com/tLotxO7.png)

## Start no projeto

```
$ node keystone
```

![Run](http://i.imgur.com/ZPJauiD.png)

![Startpage](http://i.imgur.com/DELlnHe.png)

![Admin](http://i.imgur.com/C4lWKbs.png)
