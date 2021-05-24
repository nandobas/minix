# minix
Run image minix with Dockerfile

## start

Clone project
```sh
git clone http://github.com/nandobas/minix.git
```
![](img/01.png)

go to minix directory 
```sh
cd minix
```

Build image
```sh
docker build -t image:minix .
```
![](img/02.png)

Exec container
```sh
docker run --rm -d --name container-minix image:minix
```
![](img/03.png)


And now, login into the minix terminal.<br />
Voilà!

```sh
docker exec -it container-minix ssh localhost
```
![](img/04.png)
