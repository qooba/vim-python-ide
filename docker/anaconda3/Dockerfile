FROM continuumio/anaconda3
RUN apt update && apt install curl git cmake ack g++ python3-dev vim-youcompleteme -yq
RUN sh -c "$(curl -fsSL https://raw.githubusercontent.com/qooba/vim-python-ide/master/setup.sh)"
CMD bin/bash
