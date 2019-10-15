FROM openjdk:8-jdk-alpine
ADD / /
ENV TZ='Asia/Shanghai'
RUN apk --update add curl bash ttf-dejavu && \
      rm -rf /var/cache/apk/*
CMD [""]