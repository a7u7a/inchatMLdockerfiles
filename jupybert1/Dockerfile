#jupybert1
ARG BASE_CONTAINER=jupyter/tensorflow-notebook
FROM $BASE_CONTAINER

#RUN pip install torch \
#    pip install transformers

RUN conda install -c pytorch pytorch \
    conda install -c conda-forge transformers \
    conda install -c conda-forge cloudant
