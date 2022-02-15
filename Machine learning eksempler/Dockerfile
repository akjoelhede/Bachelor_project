#Dockerfile, image, container

FROM tensorflow/tensorflow:latest-gpu

ADD gpu.py .

RUN pip install tensorflow

CMD ["python", "./gpu.py"]