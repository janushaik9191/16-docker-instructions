FROM almalinux:9
RUN dnf install nginx -y
CMD [ "nginx","-g","daemon off;" ]
# ENV sets the variables to the container,later this will be used by developers
ENV image="almalinux" \
    course="devops with aws" \
    concept="docker" \
    duration="10hrs"
