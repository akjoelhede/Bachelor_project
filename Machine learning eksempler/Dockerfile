#Dockerfile, image, container

FROM tensorflow/tensorflow:2.18.0-gpu

ADD gpu.py .

RUN pip install tensorflow

CMD ["python", "./gpu.py"]