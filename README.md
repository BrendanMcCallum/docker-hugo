# Hugo

Docker image for [Hugo](http://gohugo.io/).


## Using image

### Ordinary use

```docker run --rm -it -v `pwd`:/srv/src klakegg/hugo:0.15 [arguments]```


## Configuration

Folders:
* ```/srv/src``` - Source folder and workdir
* ```/srv/target``` - Target folder

Exposed:
* Port 1313
