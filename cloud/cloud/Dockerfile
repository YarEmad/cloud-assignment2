FROM jupyter/datascience-notebook
COPY . /cloud
WORKDIR /cloud
EXPOSE 8888

RUN pip install numpy
RUN pip install pandas


CMD ["jupyter", "notebook",  "--ip=0.0.0.0" , "--port=8888", "--no-browser","--allow-root"]
