FROM mcr.microsoft.com/dotnet/core/sdk
RUN apt update && apt install curl git cmake ack g++ python3-dev vim-youcompleteme tmux -yq
RUN sh -c "$(curl -fsSL https://raw.githubusercontent.com/qooba/vim-python-ide/master/setup_dotnet.sh)"
CMD bin/bash
