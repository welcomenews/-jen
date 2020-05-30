FROM ubuntu
RUN apt-get update && apt-get install -y python3-pip
RUN echo "ACCEPT"
RUN apt-get purge -v python3-pip
CMD tail -f /dev/null
