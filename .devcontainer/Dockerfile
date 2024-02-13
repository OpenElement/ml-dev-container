# Base File
FROM pytorch/pytorch:1.12.1-cuda11.3-cudnn8-runtime

# Updaet container
RUN apt-get update
RUN apt-get install -y \
    git

# Install required packages
RUN pip3 install --upgrade pip 
RUN pip3 install ipykernel
RUN pip3 install --upgrade tqdm

# Install Tensorflow
RUN pip3 install tensorflow