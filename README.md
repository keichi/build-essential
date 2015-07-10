# build-essential

This is a simple docker image I use to build [MPICH3](https://www.mpich.org/).
I need this because MPICH requires newer version of autotools than that
provided by apt-get. Note that building MPICH fails if you are using AUFS
as your storage driver. Devicemapper is recommended.

