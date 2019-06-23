#docker系のメモ
docker ps -a
docker ps -a -q | xargs docker kill | xargs docker rm
#adminer
host名はコンテナ名のこと