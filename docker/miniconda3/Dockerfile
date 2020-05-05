FROM continuumio/miniconda3
#RUN apt update && apt install curl git tmux -yq 
RUN apt update && apt install curl git cmake ack g++ python3-dev vim-youcompleteme tmux -yq
RUN sh -c "$(curl -fsSL https://raw.githubusercontent.com/qooba/vim-python-ide/master/setup.sh)"
RUN conda install xeus-python jupyterlab jupyterlab-git -c conda-forge
RUN jupyter labextension install @jupyterlab/debugger @jupyterlab/git
RUN pip install nbdev
CMD bin/bash
