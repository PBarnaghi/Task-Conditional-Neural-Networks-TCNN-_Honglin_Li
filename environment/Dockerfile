# hash:sha256:89404958bef363a8e38916456a6f58640f7e6b129e64e652bb9faa43a9b6b3f2
FROM registry.codeocean.com/codeocean/miniconda3:4.7.10-cuda10.1-cudnn7-ubuntu18.04

ARG DEBIAN_FRONTEND=noninteractive

RUN conda install -y \
        keras==2.2.4 \
        matplotlib==3.1.1 \
        seaborn==0.9.0 \
        tensorflow==1.13.1 \
    && conda clean -ya
