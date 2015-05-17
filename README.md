# yesod-dockerfile

dockerfile for yesod docker image

* Easy install(depandency safe)
* Fast project setup
* Without environment effect
* Respect official recommend setup

### Usage

Docker image made from this dockerfile is upped to DockerHub.
```
docker pull ynishi/yesod
```

When docker run, /mnt dir's contents is copied to /yesod and it is done yesod devel.
So, recommended mount target is /mnt and if yesod project dir is already exists, it is good to mount it /mnt.

### about Stackage image

Very simple. This is for Base of large haskell project like yesod.
