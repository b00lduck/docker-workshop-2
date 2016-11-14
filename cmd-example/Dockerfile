FROM ubuntu

ADD toilet toilet
ADD ascii9.tlf ascii9.tlf

RUN apt-get update && \
    apt-get install -y libcaca0

ENTRYPOINT ["echo"]
CMD ["hello", "docker!"]