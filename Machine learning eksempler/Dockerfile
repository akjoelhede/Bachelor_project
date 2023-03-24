#Dockerfile, image, container

FROM tensorflow/tensorflow:2.11.1-gpu

ADD gpu.py .

RUN pip install tensorflow

CMD ["python", "./gpu.py"]