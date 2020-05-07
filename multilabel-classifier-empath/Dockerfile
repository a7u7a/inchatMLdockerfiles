# for training multilabel classifier empath using simpletransformers on empatheticDialogues data. 
ARG BASE_CONTAINER=jupyter/datascience-notebook
FROM $BASE_CONTAINER

# install pytorch
RUN conda install pytorch cudatoolkit=10.1 -c pytorch

# install simpletransformers
RUN pip install simpletransformers

# install wandb
RUN pip install wandb
