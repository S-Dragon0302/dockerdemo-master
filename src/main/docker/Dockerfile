# Version 0.0.1
FROM java:8

MAINTAINER Ryuu KK "ryuu_kk@163.com"

# 环境变量
ENV WORK_PATH /usr/project
ENV APP_NAME dockerdemo
ENV APP_VERSION 0.0.1

#RUN rm -vf /var/lib/apt/lists/*
#RUN apt-get update 
#RUN apt-get install -y nginx

EXPOSE 8080

#USER
#USER user:group

#VOLUME
#VOLUME ["/usr/project", "/home/data"]

#ADD
#COPY
COPY . $WORK_PATH/$APP_NAME

#LABEL
#STOPSIGNAL
#ARG
#ONBUILD

# WORKDIR
WORKDIR $WORK_PATH

# ENTRYPOINT 
#ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom"]
# CMD
#CMD ["-jar", $APP_NAME-$APP_VERSION.jar]