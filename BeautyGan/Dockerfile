FROM python:3.6
RUN mkdir /src
COPY requirements.txt /src
# RUN pip3 install -r src/requirements.txt

RUN pip3 install imageio==2.8.0
RUN pip3 install imageio-ffmpeg==0.4.2
RUN pip3 install importlib-metadata==1.7.0
RUN pip3 install matplotlib==3.2.0
RUN pip3 install numba==0.48.0
RUN pip3 install numpy==1.18.1
RUN pip3 install opencv-python==4.2.0.32
RUN pip3 install opencv-python-headless==4.2.0.32
RUN pip3 install tensorboard==1.14.0
RUN pip3 install tensorboardX==2.1
RUN pip3 install tensorflow==1.14.0
RUN pip3 install tensorflow-estimator==1.14.0
RUN pip3 install tensorflow-gpu==1.14.0
RUN pip3 install termcolor==1.1.0
RUN pip3 install threadpoolctl==2.1.0
RUN pip3 install torch==1.6.0
RUN pip3 install torchvision==0.7.0
RUN pip3 install tqdm==4.43.0
COPY model /src/model
COPY img /src/img
COPY result /src/result
COPY Dmt.py /src
CMD ["python","src/Dmt.py"]