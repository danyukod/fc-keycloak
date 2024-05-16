FROM node:19.0

WORKDIR /home/node/app

RUN apt-get update && apt-get install -y \
    vim \
    nano \
    curl \
    wget \
    git \
    zip \
    unzip \
    iputils-ping \
    && rm -rf /var/lib/apt/lists/*

CMD ["tail", "-f", "/dev/null"]