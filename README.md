# dockers
my docker files

### pytorch jupyter

From pytorch's [repo](https://github.com/pytorch/pytorch). It just runs a notebook as root on the top of the dockerfile.

It should be hosted on dockerhub, so it runs using `nvidia-docker run --rm --ipc=host -p 1234:8888 dranax/pytorchjupyter` + your additional flags.