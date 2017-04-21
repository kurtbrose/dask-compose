FROM continuumio/anaconda
RUN conda install -y distributed && conda update distributed
ENTRYPOINT ["dask-worker", "dask-scheduler:8786"]