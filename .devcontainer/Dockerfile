FROM golang:1.21

WORKDIR /workspace/go

COPY ../ .

RUN go install \
    golang.org/x/tools/gopls@latest
