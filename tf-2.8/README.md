Create container: `docker build --file Dockerfile . -t tf-2.8`
Run container: `docker run  -u 1000:1000 --gpus all --privileged -v /dev:/dev -it --rm tf-2.8 bash`

