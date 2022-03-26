FROM ubuntu

COPY file.sh .

RUN apt-get update \
    && apt-get install -y curl  

RUN chmod +x script.sh

CMD ["./script.sh", "helsinki.fi" ]
