# Docker Setup for Family Tree 365

mkdir familytree365

cd familytree365

git clone https://github.com/familytree365/gateway-proxy.git

cd gateway-proxy

nano .env

docker-compose up -d

cd ..

git clone https://github.com/familytree365/genealogy.git

nano .env

docker-compose up -d

cd ..

git clone https://github.com/familytree365/nuxt.git

nano .env

docker-compose up -d

