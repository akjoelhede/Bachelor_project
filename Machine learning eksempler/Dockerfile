#Dockerfile, image, container

FROM tensorflow/tensorflow:2.13.0rc2-gpu

ADD gpu.py .

RUN pip install tensorflow

CMD ["python", "./gpu.py"]