# ubuntuコンテナへの接続方法
docker exec -it ubuntu script -q -c "/bin/bash"

# ubuntuコンテナからDB接続コマンド
mysql -u root -psecret2q3 -h 172.16.0.1