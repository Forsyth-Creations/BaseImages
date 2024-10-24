FROM python:3.10-slim AS builder

# Set the working directory
# WORKDIR /base

# install the opencv dependencies
# Set teh debian frontend to noninteractive
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y libglib2.0-0 libsm6 libxrender1 libxext6 ffmpeg -y
RUN apt update && apt install libpq-dev build-essential -y
