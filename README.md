## Supported tags and respective `Dockerfile` links

- [ `dev` (master/Dockerfile)](https://github.com/BenoitNorrin/docker-gitlist/blob/master/Dockerfile)
- [`0.5.0` (0.5.0/Dockerfile)](https://github.com/BenoitNorrin/docker-gitlist/blob/0.5.0/Dockerfile)

## What is GitList

GitList is an elegant and modern web interface for interacting with multiple git repositories. It allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history, diffs. See [http://gitlist.org/](http://gitlist.org/).

## How to use this image

```
docker run -it --rm --name gitlist -p 8080:80 -v -v "$PWD":/home/git/repositories/ bnorrin/docker-gitlist
```
