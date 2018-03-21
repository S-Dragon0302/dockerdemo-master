# Version 0.0.1
FROM java:8
MAINTAINER Ryuu KK "junjie@miduchina.com"

# 环境变量
ENV WORK_PATH /data/
ENV APP_NAME @project.build.finalName@.@project.packaging@
ENV APP_VERSION @project.version@

EXPOSE 8080

#ADD
ADD $APP_NAME $WORK_PATH/

#COPY
COPY . $WORK_PATH/

# WORKDIR
WORKDIR $WORK_PATH

# ENTRYPOINT 
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom"]

# CMD
CMD ["-jar", "@project.build.finalName@.@project.packaging@"]