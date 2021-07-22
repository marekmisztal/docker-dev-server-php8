# My Docker dev environment
PHP 8.0, Apache 2.4

# Usage
1. Go to docker dir
2. Copy/move .env.dist to .env
3. Change what you need in .env (set USER_ID to your UID)
4. run `docker network create serverdev_network`
3. run `docker-compose up -d` or ./start
