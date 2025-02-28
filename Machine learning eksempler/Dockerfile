#Dockerfile, image, container

FROM tensorflow/tensorflow:2.19.0rc0-gpu

ADD gpu.py .

RUN pip install tensorflow

CMD ["python", "./gpu.py"]