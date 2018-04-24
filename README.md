# HPC-AI-TU-2018

### System requirents
- Ubuntu 16.04 x86_64
- Python 2.7
- Docker 18.03 or newer
- CUDA 7.5 or newer
- cuDNN

### Hardware requirements
```
CPUs    : 4 cores
RAM     : 8-32 GB
Disks   : 40 GB
GPUs    : 1
```


### Docker build
```
# Build an image using the Dockerfile at current location
# Example: docker build -t [name] .
docker build -t my_tensorflow .    
```

### Running a docker image
```
docker rum -name my_tensorflow_instance -i -t my_tensorflow
```