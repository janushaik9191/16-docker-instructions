FROM almalinux:9
RUN mkdir /tmp/docker
# for switching between directories cd command is not worked in docker,we can use workdir 
# it shows current work location
WORKDIR /tmp/docker
RUN pwd
RUN echo "Hello" > hello.txt
CMD ["sleep", "100"]