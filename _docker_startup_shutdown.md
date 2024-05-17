https://cloud.nextcloud.com/s/iyNGp8ryWxc7Efa?dir=undefined&path=%2F1%20Setting%20up%20a%20development%20environment%2FTutorial%20for%20Windows&openfile=7087340

In folder /home/users/ubuntu/2024/05_nextcloud_Maps_PR run the following:

```
docker compose up -d nextcloud
```

then you can open the browser and go to http://nextcloud.local

for updating the maps app from source, see the Dockerfile.php-make in the workspace/server/apps-extra/maps folder

--

To stop the container run:

```
docker compose down
```

Resetting all data in the container:

```
docker compose down -v
```

# Maps setup

https://github.com/nextcloud/maps/?tab=readme-ov-file#-development-setup

-   see Dockerfile.php-make
