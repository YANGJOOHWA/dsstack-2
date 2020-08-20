FROM jupyter/all-spark-notebook
#FROM jupyter/scipy-notebook

USER root

RUN pip install --proxy=${http_proxy}\
    psycopg2-binary\
    minio\
    tensorflow\
    pyngrok\
    streamlit\
    Flask\
    implicit\
    gensim

USER jovyan
