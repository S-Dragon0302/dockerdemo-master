# Version 0.0.1
FROM java:8

MAINTAINER Ryuu KK "ryuu_kk@163.com"

# 环境变量
ENV WORK_PATH /home/project/dockerdemo
ENV APP_NAME dockerdemo
ENV APP_VERSION 0.0.1
ENV PACKAGE package.tgz

#RUN rm -vf /var/lib/apt/lists/*
#RUN apt-get update 
#RUN apt-get install -y nginx

EXPOSE 8080

#USER
#USER user:group

#VOLUME
VOLUME ["/home/project", "/tmp/data"]

#ADD
ADD $PACKAGE $WORK_PATH/

#COPY
COPY . $WORK_PATH/

#LABEL
#STOPSIGNAL
#ARG
#ONBUILD

# WORKDIR
WORKDIR $WORK_PATH

# ENTRYPOINT 
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar"]
# CMD
CMD ["$APP_NAME.jar"]

