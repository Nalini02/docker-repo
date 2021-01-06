#######  3rd Example---

#######   START   ######

####  creating WORKDIR and setting the ENV-variables  ###


From redis
RUN yum install tree
RUN yum install nano
RUN mkdir project

####  creating working directory as docker-work #####
WORKDIR docker-work

#####docker-work will be created and all the instructions will be executed in the workdir.

COPY ./ .

#### defining the environment variables  ###

ENV X=100
ENV CITY=Ponnur
ENV STATE=AP
