FROM mcr.microsoft.com/devcontainers/cpp:1-debian-12

RUN apt-get update && apt-get install -y --no-install-recommends \
    build-essential \
    cmake \
    git \
    pkg-config \
    openmpi-bin \
    libopenmpi-dev \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
