# redis-client-ec2

- install

```
sudo yum install -y gcc
wget http://download.redis.io/redis-stable.tar.gz && tar xvzf redis-stable.tar.gz && cd redis-stable && make
sudo cp src/redis-cli /usr/bin/
```

- run redis client

```
redis-cli -h HOST
```
