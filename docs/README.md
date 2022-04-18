```shell
cnpm install
npm run dev

find . -name "Dockerfile"|xargs -I {} cat {}|grep nginx
find . -name "nginx.conf"
```
