FROM almalinux:9 
ENV course="devops with aws" \
    trainer="vinod" \
    duration="120HRS"
#here user1 is key, someuser is default value
#ARG user1=someuser --> we cannot overwrite this
# we can overwrite this
ARG ${username:-some_user} 
RUN echo "Hello ${username}" > /tmp/devops.txt
CMD ["sleep", "100"]