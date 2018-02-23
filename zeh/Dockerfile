# Ze container, o comportado
# Este container executa tarefas simples e sera o container que vai sofrer com seus vizinhos mau comportados
FROM alpine:latest

LABEL maintainer="amioranza@mdcnet.ninja"
LABEL description="Zeh container"

WORKDIR /

COPY zeh /zeh

ENTRYPOINT [ "/zeh" ]