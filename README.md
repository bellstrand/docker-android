[![CircleCI (all branches)](https://img.shields.io/circleci/project/github/bellstrand/docker-android.svg)](https://circleci.com/gh/bellstrand/docker-android)

# Docker Android
### Based on [bellstrand/docker-java8](https://github.com/bellstrand/docker-java8)
----
### Pull from Docker Hub
```
docker pull bellstrand/android:$VERSION
```

### Run image
```
docker run -it bellstrand/android:$VERSION bash
```

### Use as base image
```Dockerfile
FROM bellstrand/android:$VERSION
```