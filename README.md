```
docker images
REPOSITORY                   TAG                 IMAGE ID            CREATED             VIRTUAL SIZE
hmalphettes/alpine-zulujre   latest              5ecaeda3bb94        15 seconds ago      66.37 MB
```

Smallest Java Runtime Environment in an alpine docker container
Uses Zulu's build of the compact3 profile of the openjdk as found in https://github.com/delitescere/docker-zulu/tree/master/jre

Help wanted:
------------
I am looking for an updated jre build: https://github.com/delitescere/docker-zulu/issues/5

Credits:
--------
- Frolvlad's alpine-glibc base image
- Delitescere's docker-zulu (https://github.com/delitescere/docker-zulu) where we get a hold of the really small jre build.
- Azulsystems and their builds of the OpenJDK.

License:
--------
This Dockerfile is public domain.
