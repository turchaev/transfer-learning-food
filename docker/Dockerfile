# https://ngc.nvidia.com
FROM nvcr.io/nvidia/tensorflow:18.09-py3

LABEL maintainer="Dmitry Korobchenko <dkorobchenko@nvidia.com>"

RUN pip --no-cache-dir install \
    numpy==1.14.5 \
    imageio==2.3.0 \
    scikit-image==0.14.0 \
    jupyter==1.0.0 \
    matplotlib==3.0.0

WORKDIR /transfer-learning
