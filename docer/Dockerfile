FROM ubuntu:stable
RUN  apt install py-pip &&  pip install awscli
RUN apt --purge -v del py-pip
CMD tail -f /dev/null
