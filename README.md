# Shadow.BG
![Screenshot](https://i.imgur.com/FAC6GCC.png)

Deployed [backend (Go)](https://github.com/vukilis/shadowbg-backend/tree/79ceaa36b6e2d467096a517f37763a003b988292) and [frontend (Next.js)](https://github.com/vukilis/shadowbg-frontend/tree/75e62fd98c505adfc0286de03e944481b43859c7) with Docker  
Easier search RARBG backup database

###### Prerequisites
- [Docker](https://docs.docker.com/desktop/)

###### Steps to build
You need to [download]() the `rarbg_db.zip` file, unzip it and rename `rarbg_db.sqlite` to `db.sqlite` (Or you can change the `main.go` code to use any other name you want to rename the file to. After that, move `db.sqlite` to shadowbg-backend folder.
````
git clone https://github.com/vukilis/shadowbg && cd shadowbg
cp shadowbg-frontend/.env.example shadowbg-frontend/.env
sudo docker-compose -f docker-compose-prod.yml up -d
````
###### Mention
Forked from [xav1erenc](https://github.com/xav1erenc) who wrote app in Go and Next.js