FROM continuumio/anaconda
RUN conda install -y distributed && conda update distributed
RUN conda install -y distributed bokeh
ENTRYPOINT ["dask-scheduler"]