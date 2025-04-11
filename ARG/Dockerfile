ARG version
# to declare version to the base image and it is valid before FROM and until FROM
FROM almalinux:${version:-9}
ARG course="DevOps with AWS" \
    duration="120hrs"
# if we want to use ARG in containers declare as below
ENV duration=$duration
RUN echo "Course: $course, duration: $duration, version: $version"
CMD ["sleep","100"]