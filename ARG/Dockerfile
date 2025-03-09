FROM almalinux:9
ENV course="Devops with AWS" \
    trainer="siva" \
    duration="120"
# here user is key and someuser is default value
ARG ${username:-some_user}
Run echo "Hello ${trainer}" > /tmp/devops.txt
CMD ["sleep", "100"]    