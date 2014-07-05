Library
========

The library consists of two subprojects (the frontend as gui and a RESTful backend). The testfolder contains some load, performance and seleniumtests (they will be triggered all 24h by a cronjob).

## Load submodules
The project consists of two submodules (backend and frontend). The following steps will load all submodules:

```
git submodule init
git submodule update
```

## Update submodules
The submodules are links to standalone-git-repositories to update these links just run:

> git submodule foreach git pull origin master

