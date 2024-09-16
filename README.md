Link To Install : https://betterstack.com/community/guides/scaling-go/redis-caching-golang/

# Using Redis in Go

This repo contains various examples of using Redis in Go. You'll learn how to
perform the following actions:

- Connect to a Redis server from your Go program.
- Add data to a Redis database.
- Read previously cached data in the database.
- Update a cached value.
- Delete a cached value.

# Check in terminal

1. go to redis terminal using : redis-cli
2. If Redis is running on a remote server, specify the host and port: redis-cli -h <host> -p <port>
3. Set Key-Value Pair using : SET mykey "value"
4. Get value using key : GET key
5. List All Keys : KEYS\*
6. Delete Kye : DELETE key
7. Check if key exists : EXISTS key
8. If Redis is configured with a password, you'll need to authenticate after connecting. You can do this with: AUTH "password"
