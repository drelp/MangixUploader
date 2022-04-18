```shell
cnpm install
npm run dev

npm run build
cd docker
rm -rf dist
cp -r ../dist/ .

sudo docker-compose up mangix-fe
sudo docker-compose up -d mangix-fe
sudo docker-compose stop mangix-fe
sudo docker-compose rm mangix-fe

find . -name "Dockerfile"|xargs -I {} cat {}|grep nginx
find . -name "nginx.conf"
```
