# aria2 with yaaw 

* [aria2](https://aria2.github.io)
* [yaaw](https://github.com/binux/yaaw) 

[![CircleCI](https://circleci.com/gh/hitian/docker-aria2.svg?style=svg)](https://circleci.com/gh/hitian/docker-aria2)

### Build

`docker build -t="aria2-arm32v6" .`

### Run

`docker run --name aria2c -v /dir/for/downloads:/downloads -p 8080:80 -p 6800:6800 -d aria2-arm32v6`

### Usage

open `http://127.0.0.1:8080/`