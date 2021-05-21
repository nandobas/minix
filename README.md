# minix
Run image minix with Dockerfile

#start
docker build -t imagem:minix .
docker run --rm -d --name minix-container imagem:minix
