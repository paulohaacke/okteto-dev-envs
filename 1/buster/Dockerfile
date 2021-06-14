FROM rust:1-buster

RUN apt-get update && apt-get install -y git vim \
  && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace

COPY bashrc /root/.bashrc

CMD ["bash"]
