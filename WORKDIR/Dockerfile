FROM almalinux:9 
RUN dnf install nginx -y 
RUN mkdir /tmp/work-dir
WORKDIR /tmp/work-dir
RUN pwd 
RUN echo "Hello This is work dir" > hello.txt 
CMD ["sleep", "100"]