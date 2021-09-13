FROM python:2.7
LABEL maintainer="Daneshwari_K"
WORKDIR /techtrends
COPY ./techtrends /techtrends
RUN pip install -r requirements.txt
RUN python init_db.py
EXPOSE 3111
CMD ["python","app.py"]
