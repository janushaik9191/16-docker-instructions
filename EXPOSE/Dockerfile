FROM almalinux:9
RUN dnf install nginx -y
CMD [ "nginx","-g","daemon off;" ] 
# EXPOSE instruction used to expose the ports open by the container but it does't open port 
EXPOSE 80 