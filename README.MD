<h1>How.</h1>

local
1. ssh root@ip

local
2. scp docker-compose2.yaml root@46.101.242.190/:/home/dev/wordpress

CREATE static files from wordpress instance.
In current working directory creates folder named by ip adress. 
In side are created files from website.

wget --mirror --convert-links --backup-converted --adjust-extension http://46.101.242.190/


3. Push files to git repo. 
4. https://github.com/ZSzymon/cv.git branch gh-pages.
5. scp root@46.101.242.190/:/home/dev/wordpress/tmp .
docker cp <container_id>:<src path> <dest path>
