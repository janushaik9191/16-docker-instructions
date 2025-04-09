FROM almalinux:9
RUN rm -rf /usr/share/nginx/html/index.html
# COPY used copy local files or directiories to the image
COPY index.html /usr/share/nginx/html/index.html
RUN dnf install nginx -y
CMD [ "nginx","-g","deamon off;" ]