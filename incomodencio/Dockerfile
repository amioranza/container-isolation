# Incomodencio container, o consumidor de i/o
# Este container executa tarefas de i/o intensiva
FROM alpine:latest

LABEL maintainer="amioranza@mdcnet.ninja"
LABEL description="Incomodencio container"

WORKDIR /

COPY incomodencio /incomodencio

ENTRYPOINT [ "/incomodencio" ]