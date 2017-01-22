Let's Docker - Platform v1.0
==============

* [Preparation](#preparation)
* [Installation](#installation)
* [Credentials](#credentials)
* [Urls](#urls)

## Preparation

Clone "letsdocker" repository into /gits folder.

```
git clone https://github.com/lets-docker/letsdocker
```

Clone platform repository into the root folder.

```
git clone https://github.com/lets-docker/platform.git
```

End of this, your directory tree should be like below:

```
├── gits
│   └── letsdocker
├── platform
│   └── docker-compose.yml
```

## Installation

In your platform directory, run below command;

```
docker-compose -p "Let's Docker" up -d --build
```

## Credentials

#### MYSQL
```
      MYSQL_ROOT_PASSWORD: wordpress
      MYSQL_DATABASE: wordpress
      MYSQL_USER: root
      MYSQL_PASSWORD: wordpress
```

## URLS
#### Let's Docker

```
http://localhost:90
```
#### Phpmyadmin

```
http://localhost:91
```
