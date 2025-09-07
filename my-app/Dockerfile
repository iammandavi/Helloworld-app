FROM python 
ENV MONGO_INITDB_ROOT_USERNAME=admin \ 
    MONGO_INITDB_ROOT_PASSWORD=qwerty 
RUN mkdir -p /my-app-image 
WORKDIR /my-app-image 
COPY . /my-app-image 
CMD ["python", "app.py"]