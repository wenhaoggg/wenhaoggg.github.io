---
layout: post
title: Docker Basics
date: 2025-10-15 02:56
description: Docker tips
tags: Docker
categories: Data-Science
---

List all images

```
docker images
docker image ls
```

List all containers, including exited and stopped ones

```
docker ps -a
```

Stop containers using ID

```
docker stop #$(docker ps -aq) # -q quiet, only give ID
```

Remove containers after stopping them

```
docker rm #$(docker ps -aq)
```

Delete images after removing containers created from them

```
docker rmi 
```
