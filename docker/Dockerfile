FROM jupyter/datascience-notebook

RUN pip install --upgrade pip \
    && pip install datapackage \
    && pip install --upgrade seaborn \
    && pip install tensorflow \
    && pip install plotly_express \
    && pip install --upgrade scikit-learn \
    && pip install geopy \
    && pip install xgboost


WORKDIR '/home/jovyan/work/code/'
