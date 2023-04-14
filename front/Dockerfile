FROM golang

COPY dispatcher.go .
COPY static/ ./static

RUN go build dispatcher.go

EXPOSE 80

CMD [ "./dispatcher" ]