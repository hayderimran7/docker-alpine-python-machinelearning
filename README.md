[![Docker Image](https://images.microbadger.com/badges/version/hayderimran7/docker-alpine-python-machinelearning.svg)](https://microbadger.com/images/hayderimran7/docker-alpine-python-machinelearning "Get your own version badge on microbadger.com")


Python Machine Learning tools Docker image
==========================================

This image is based on
[Alpine Linux Python 3.5 image](https://hub.docker.com/r/frolvlad/alpine-python3/),
which is only a 60MB image, and contains popular Machine Leaning tools:

* numpy
* pandas
* scipy
* scikit-learn
* matplotlib

Download size of this image is only:

[![Docker Image Size](https://images.microbadger.com/badges/image/hayderimran7/docker-alpine-python-machinelearning.svg)](https://microbadger.com/images/hayderimran7/docker-alpine-python-machinelearning "Get your own image badge on microbadger.com")


Usage Example
-------------

```bash
$ docker run --rm frolvlad/alpine-python-machinelearning python3 -c 'import numpy; print(numpy.arange(3))'
```

Once you have run this command you will get printed `array([0, 1, 2])` from Python!
