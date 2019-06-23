#docker系のメモ  
docker ps -a  
docker ps -a -q | xargs docker kill | xargs docker rm  
#adminer  
データベース種類:PostgreSQL  
サーバ:コンテナ名(postgresql)  
ユーザ名:root  
パスワード:root  
データベース:(空欄)  