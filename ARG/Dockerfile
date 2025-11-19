ARG VERSION=9
FROM almalinux:${VERSION}
ENV course="DevOps with Docker" \
    author="Rahul Gattu" \
    version="1.0"
# here user1 is key and someuser is default value if no value is passed during build time
# to override default value use --build-arg user1=newuser
ARG USER=someuser
ENV USER1=$USER
RUN echo "The user1 value is : $USER" > /tmp/devops.txt
CMD ["sleep","100"]