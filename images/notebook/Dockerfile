FROM continuumio/anaconda
RUN conda install jupyter -y
ENTRYPOINT ["jupyter", "notebook", "--notebook-dir=/opt/notebooks", "--ip='*'", "--port=8888", "--no-browser"]