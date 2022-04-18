```shell
cnpm install
npm run dev

cd docker

find . -name "Dockerfile"|xargs -I {} cat {}|grep nginx
find . -name "nginx.conf"
```
