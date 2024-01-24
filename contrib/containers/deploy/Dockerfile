FROM phusion/baseimage:focal-1.0.0
LABEL maintainer="SmartLoopAI Developers <dev@smartloopai.org>"
LABEL description="Dockerised SmartLoopAI, built from Travis"

ARG USER_ID
ARG GROUP_ID

ENV HOME /home/smartloopai

# add user with specified (or default) user/group ids
ENV USER_ID ${USER_ID:-1000}
ENV GROUP_ID ${GROUP_ID:-1000}
RUN groupadd -g ${GROUP_ID} smartloopai && \
    useradd -u ${USER_ID} -g smartloopai -s /bin/bash -m -d /home/smartloopai smartloopai && \
    mkdir /home/smartloopai/.smartloopai && \
    chown ${USER_ID}:${GROUP_ID} -R /home/smartloopai

COPY bin/* /usr/local/bin/

RUN chmod a+x /usr/local/bin/*

USER smartloopai

VOLUME ["/home/smartloopai"]

EXPOSE 15693 9999 25693 25694

WORKDIR /home/smartloopai
