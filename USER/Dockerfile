FROM almalinux:9
RUN useradd expense
USER expense
CMD ["sleep", "100"]

# containers with root access is major security issue it can access host storage so that atleast last instruction should run with normal user