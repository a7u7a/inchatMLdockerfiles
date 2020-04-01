#jupybert1
ARG BASE_CONTAINER=jupyter/tensorflow-notebook
FROM $BASE_CONTAINER

RUN conda install -c pytorch pytorch
RUN conda install -c conda-forge transformers
RUN conda install -c conda-forge cloudant
