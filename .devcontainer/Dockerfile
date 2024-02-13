FROM pytorch/pytorch:1.12.1-cuda11.3-cudnn8-runtime

RUN apt-get update
RUN apt-get install -y \
    git

RUN pip3 install --upgrade pip 
RUN pip3 install ipykernel
RUN pip3 install --upgrade tqdm