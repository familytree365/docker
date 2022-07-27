# Docker Setup for Family Tree 365

mkdir familytree365
cd familytree365
git clone https://github.com/familytree365/gateway-proxy.git
cd gateway-proxy
docker-compose up -d
cd ..
git clone https://github.com/familytree365/genealogy.git
docker-compose up -d
cd ..
git clone https://github.com/familytree365/nuxt.git
docker-compose up -d
