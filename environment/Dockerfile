# hash:sha256:df64d0686bb4f0516d178542b18bb193375fafc3f83e906a493d93b7bef72dea
FROM registry.acmecorp-edge.codeocean.com/codeocean/jupyterlab:3.4.4-miniconda4.12.0-python3.9-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip install -U --no-cache-dir \
    matplotlib \
    numpy
