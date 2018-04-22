# [**drode**](https://github.com/thonatos/drode)

A Node.js CI Application inspired by Drone.

## Introduction

这个项目的初衷，是用较为简单，同时也易于排查的方式，去实现以Docker为基础的CI/CD。

所以暂定将使用到以下技术/技术栈：

* Docker
  * dockerode
  * 
* Redis
* Node.js
  * socket.io
  * socket.io-stream
* React.js
  * ant-design

整个项目将会以socket.io为基础，实现不同类型client与server的通讯

## Server

### Table of Contents

* client
  * id
  * region
* repo
  * url
  * auth
  * build
    * region
* image
  * repo
  * auth

> be continued

## Client

### Table of Contents

* client
  * register
* git
  * clone
* docker
  * build
  * push

> be continued

## CLI
> be continued

## Reference

* [https://docs.docker.com/engine/api/](https://docs.docker.com/engine/api/)



