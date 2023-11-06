#Dockerfile, image, container

FROM tensorflow/tensorflow:2.15.0rc1-gpu

ADD gpu.py .

RUN pip install tensorflow

CMD ["python", "./gpu.py"]