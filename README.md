# Docker Setup for Family Tree 365

## Create root directory

mkdir familytree365

## Change directory

cd familytree365

## Clone Gateway Proxy

git clone https://github.com/familytree365/gateway-proxy.git

## Change directory

cd gateway-proxy

## Setup configuration file with your editor of choice

nano .env

## Start Docker Compose

docker-compose up -d

## Change back to root install directory

cd ..

## Clone Genealogy API Backend

git clone https://github.com/familytree365/genealogy.git

## Setup configuration file with your editor of choice

nano .env

## Start Docker Compose

docker-compose up -d

## Change back to root install directory

cd ..

## Clone Nuxt Frontend

git clone https://github.com/familytree365/nuxt.git

## Setup configuration file with your editor of choice
nano .env

## Start Docker Compose

docker-compose up -d


## You should now be able to access your install at the URLs specified in .env
