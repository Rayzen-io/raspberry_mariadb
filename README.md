# Rayzen docker for Raspberry (MariaDB version)
This is a repository to run Symfony inside docker container using:
- PHP 8.0
- Nginx
- MariaDB
## How to use ?
Important note, a directory `data` (database storage) and `src` (for Symfony project) are required before compose the volumes. In Docker folder:
```
$ mkdir database/data
// Clone symfony project inside a src folder one level above
$ git clone <repository_ssh> ../src
$ docker-compose up
```