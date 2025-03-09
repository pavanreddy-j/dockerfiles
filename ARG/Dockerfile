FROM almalinux:9
ENV course="Devops with AWS" \
    trainer="siva" \
    duration="120"
# here user is key and someuser is default value
ARG ${username:-some_user}
RUN echo "Hello User: ${username}"
CMD ["sleep", "100"]    