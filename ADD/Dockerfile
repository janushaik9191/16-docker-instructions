FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# ADD instruction downloads code from internet directly
ADD https://raw.githubusercontent.com/daws-81s/expense-infra-dev/refs/heads/main/readme.MD /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
# ADD instruction copy file from local to image and extract also done
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]