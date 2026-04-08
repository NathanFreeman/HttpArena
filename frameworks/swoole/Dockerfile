FROM mariasocute/swoole:6.2.0

WORKDIR /swoole
ADD ./swoole.php /swoole
ADD ./SQLite.php /swoole
ADD ./PostgreSQL.php /swoole

EXPOSE 8080
CMD ["php", "-dmemory_limit=2048M","/swoole/swoole.php", "start"]
