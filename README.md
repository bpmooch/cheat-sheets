# cheat-sheets
shortcuts for things
## Docker
### [cp](https://docs.docker.com/engine/reference/commandline/cp/) `docker cp [CONTAIER:SRC] [LOCAL_DEST]` `docker cp [LOCAL_SRC] [CONTAINER:DEST]`
Copy to/from containers
#### [--follow-link, -L](https://docs.docker.com/engine/reference/commandline/cp/#options) `docker cp -L [SRC] [DEST]`
## jq
### [`cat package.json | jq '.scripts'`](http://www.compciv.org/recipes/cli/jq-for-parsing-json/)
print `script` property of json object
