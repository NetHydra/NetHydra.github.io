## This page is hosted by GitHub.

### Content.

The content of every Documentations and posts is stored in `content` directory.
every post/documentations has writen in markdown format (.md).

```
content
├── _installations
├── _introductions
├── _policy
├── _posts (News, announcments, release)
├── _tools
└── _trouble
```

### Build and Deploy

This pages is uses `jekyll` engine to build this page you need `gem` `bundler`

to build this page and deploy it you need to clone this repository

```
ubuntu@ubuntu.local:~# git clone https://github.com/nethydra/nethydra.github.io/
```
install dependencies
```
ubuntu@ubuntu.local:~# cd nethydra.github.io
ubuntu@ubuntu.local:~# bundle install
```
Deploying
```
ubuntu@ubuntu:~# bundle exec jekyll server
# the default port is listened on 4000 (http://localhost:4000)
```

