1. To start (with a .sql file loaded)

### `docker-compose up -d`

2. login in to the newly created mysql container and check the db content

### `docker exec -it <container> bash`

### `mysql -u root -p`

### `password`

### `show databases;`

### `use test;`

### `show tabels;`

### `select * from users;`

3. or use thrid party UI tool, login with root/password @ 127.0.0.1:33060

4. To stop

### `docker-compose down`

### `docker stop <container>`

### `docker rm <container>`

5. after you build the image, you can import and export the docker image

### `docker save <my_local_image> > xxx.tar`
### `docker load --input xxx.tar`
