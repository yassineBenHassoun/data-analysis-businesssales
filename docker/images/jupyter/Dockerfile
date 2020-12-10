FROM python:3.8

EXPOSE 8888

RUN pip install \
  numpy \
  pandas\
  notebook \
  mysql \
  mysqlclient \
  mysql-connector-python \
  matplotlib \
  scipy \
  seaborn


RUN mkdir -p  /lab

WORKDIR /lab

ENTRYPOINT [ "jupyter" ]
CMD [ "notebook","--allow-root","--ip=0.0.0.0"]
