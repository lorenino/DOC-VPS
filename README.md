# DOC-VPS


## Docker 

### Get Info 

docker images
docker container 

### Get Images

#### Rechercher 

docker search <image>

#### Download

docker pull <nom de l’image>

#### Delete 

docker rmi <nom de l’image>

### Get Container

#### Listing 

docker ps -a

#### Launch 

#### p
docker run <nom de l’image>

#### i
docker run -d <nom de l’image> tail -f /dev/null

#### Go in 

docker exec -it <id du conteneur> bin/bash

#### Start/Stop

docker stop <id du conteneur>
docker start <id du conteneur>

#### Delete 

docker rm <id du conteneur>

### Action on File 

#### cp/p

docker cp <nom du fichier> <id du conteneur>:/< nom du fichier >

#### run a file in a container or image

docker exec -it <id> python /<nom du fichier> <Phrase de test>


## Bitcoind

### Info ponct

bitcoin-cli -getinfo
bitcoin-cli getblockchaininfo
bitcoin-cli getnetworkinfo
bitcoin-cli getpeerinfo

### Info Raw

tail -f ~/.bitcoin/debug.log

## Github

### Commit

git add .
git commit -m "Votre message de commit"
git push origin main
