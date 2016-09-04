# base16-builder-docker
base16-builder in a Docker container

To generate the default dark base16 theme for gnome-terminal run:

```
docker run -it --rm mindfulmonk/base16-builder-docker base16-builder -s default -t gnome-terminal -b dark 
```

or pipe to a file:

```
docker run -it --rm mindfulmonk/base16-builder-docker base16-builder -s default -t gnome-terminal -b dark > base16.sh
```


Huge thanks to:

https://github.com/base16-builder/base16-builder/
https://github.com/mhart/alpine-node

