
To rebuild for every new version

docker build --build-arg VERSION=5.1.17 -t sairamkunala/tiddlywiki5:5.1.17 .

Tiddlywiki5 - https://github.com/Jermolene/TiddlyWiki5

Current Version: 5.1.17

HomePage - https://www.npmjs.com/package/tiddlywiki

Dockerfile reused from https://github.com/djmaze/tiddlywiki-docker 

sudo docker run -d -p 8080:8080 sairamkunala/tiddlywiki5

sudo docker run -e USERNAME=username PASSWORD=secret -d -p 8080:8080 -v $HOME/Documents/tiddlywiki:/var/lib/tiddlywiki sairamkunala/tiddlywiki5

Default auth is user / wiki




