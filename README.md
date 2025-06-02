sudo su
apt update
apt upgrade
docker-compose up -d
( ●●● ports 80 🌐)
docker-compose run --rm panel php artisan p:user:make
