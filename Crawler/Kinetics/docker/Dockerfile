FROM continuumio/miniconda3

RUN apt-get update

RUN apt-get install -y youtube-dl \
    ffmpeg \
    git \
    vim


WORKDIR "/workspace"

RUN pip install --no-cache-dir Cython \
    pandas \
    joblib 

RUN pip install --upgrade git+https://github.com/ytdl-org/youtube-dl.git@master
    
RUN git clone https://github.com/paolorota/ActivityNet.git
  
