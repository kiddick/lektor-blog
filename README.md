Sources of my personal blog on github pages
===========================================

There is some instructions for easy development and blog settings.

Firstly install lektor (https://getlektor.com)

`curl -sf https://www.getlektor.com/install.sh | sh`

To run project:

```
$ cd lektor-blog
$ lektor server
```

Temporary solution for markdown-highlighter plugin:

* create `packages` folder
* clone forked plugin
* run `lektor server`

To deploy via https on github pages:
```
lektor build && lektor deploy ghpageshttps
lektor build && lektor deploy ghpages
```
