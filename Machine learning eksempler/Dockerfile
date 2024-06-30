#Dockerfile, image, container

FROM tensorflow/tensorflow:2.16.2-gpu

ADD gpu.py .

RUN pip install tensorflow

CMD ["python", "./gpu.py"]