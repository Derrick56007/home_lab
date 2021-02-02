#FROM balenalib/raspberry-pi-debian:latest
FROM debian:latest

RUN apt-get update && apt-get install -y calibre

#CMD []
CMD ["calibre-server", "/books"]
