# Estorvaldo container, o consumidor de cpu
# Este container executa tarefas de cpu intensiva
FROM alpine:latest

LABEL maintainer="amioranza@mdcnet.ninja"
LABEL description="Estorvaldo container"

WORKDIR /

COPY estorvaldo /estorvaldo

ENTRYPOINT [ "/estorvaldo" ]