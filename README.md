# RPI Minio

* Master : [![coverage report](https://gitlab.com/zeiot/minio/badges/master/coverage.svg)](https://gitlab.com/zeiot/minio/commits/master)

Docker image of [Minio][] to use on ARM (7 & 8) devices

Configure binfmt-support on the Docker host (works locally or remotely, i.e: using boot2docker):

    $ docker run --rm --privileged multiarch/qemu-user-static:register --reset

Then you can run an armhf image from your x86_64 Docker host :

    $ make run version=x.x

Or build :

    $ make build version=x.x


## License

See [LICENSE](LICENSE) for the complete license.


## Changelog

A [ChangeLog.md](ChangeLog.md) is available.


## Contact

Nicolas Lamirault <nicolas.lamirault@gmail.com>


