# 日本語が扱えるuplatex用dockerfile

[Original](https://hub.docker.com/r/paperist/alpine-texlive-ja/)


- build `docker build -t docker-tex .`
- run `docker run --rm -it -v $PWS:/workdir docker-tex`

## configuration

- use `.latexmkrc` of `dotfiles/.latexmkrc`
- install  `jlisting.sty`
