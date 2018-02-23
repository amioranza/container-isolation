# Perturbalino container, o consumidor de memoria
# Este container executa tarefas de consumo de memoria
FROM alpine:latest

LABEL maintainer="amioranza@mdcnet.ninja"
LABEL description="Perturbalino container"

WORKDIR /

COPY pertubalino /perturbalino

ENTRYPOINT [ "/perturbalino" ]