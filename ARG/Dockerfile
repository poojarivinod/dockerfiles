FROM almalinux:9 
ENV course="devops with aws" \
    trainer="vinod" \
    duration="120HRS"
# here user1 is key, someuser is default value
# we can overwrite this
ARG user1=vinod
RUN echo "Hello ${username}" > /tmp/devops.txt
CMD ["sleep", "100"]