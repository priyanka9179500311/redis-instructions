# redis-instructions
redis-instructions

redis-cli

set key value

get key

keys *

del key

mset key value key value

mget key key key

ttl set

flushall

expire key second

setex key second value

setex name2 40 "vikki"

setnx key value

incr key

decr key

setnx name "sunil"

append key value

strlen key

psetex key milliseconds value

msetnx key value [key value.....]

incrby key value

decrby key value

psetex key milliseconds value

append key value

strlen key

msetnx key value[key value...]

hset key field value

hget key field

hmset key field value[field value.....]

hmset key field[field...]

hgetall key

hlen key

hstrlen key field

hkeys key

hvals key

hdel key field [field...]

hsetnx key field value

hexists key field

hincrby key field increment

hincrbyfloat key field increment

lpush key value[value....]

rpush key value[value....]

lpop key

rpop key

llen key

linsert key before|after pivot value

sadd key member[member...]

scard key

sunion key[key...]

sinter key[key...]

sdiff key[key...]

smembers key

srem key member[member....]

spop key [count]

sdiffstore destination key[key...]

sinterstore destination key[key...]

sunionstore destination key[key...]

sismember key member

zadd key score value

zcard key

zcount key min max

zrange key start stop

zrange key start stop [withscores]

zrem key member [withscores]

zrank key member

zrevrank key member

zrangebyscore key min max [withscores]


