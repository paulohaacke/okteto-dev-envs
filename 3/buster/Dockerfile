FROM python:3-buster

RUN apt-get update && apt-get install -y \
  git \
  vim \
  jq \
  && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace

COPY bashrc /root/.bashrc

CMD ["bash"]
