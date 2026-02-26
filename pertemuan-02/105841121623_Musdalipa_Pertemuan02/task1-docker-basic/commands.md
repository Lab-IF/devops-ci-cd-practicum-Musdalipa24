# Docker Basic Commands

## Menjalankan Nginx
docker run -d -p 8080:80 --name mynginx nginx

## Melihat container aktif
docker ps

## Menghentikan container
docker stop mynginx

## Menghapus container
docker rm mynginx