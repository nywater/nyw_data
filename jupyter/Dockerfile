# Extends jupyter/datascience-notebook
FROM jupyter/datascience-notebook

# Copies Jupyter notebooks used to format restaurant data
COPY IngestData.ipynb /home/jovyan/IngestData.ipynb

# Installs pymongo
RUN pip install pymongo