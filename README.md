# DynomiteDB C/C++ build image

Build DynomiteDB components written in C/C++.

> Do not use this image directly as it is referenced within each application's build image.

# Manually build the `build-c` image

This image is automatically built on DockerHub. However, if you want to manually build this image then execute the commands below.

Clone the repo.

```bash
mkdir ~/repos && git clone https://github.com/DynomiteDB/docker-build-c.git
```

`cd` into the repo.

```bash
cd ~/repos/docker-build-c
```

Build the image.

```bash
docker build -t dynomitedb/build-c .
```

