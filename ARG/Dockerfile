ARG version
# version is a variable, if variable is not given then it will take default value 9
FROM almalinux:${version:-9}
ENV course="devops with aws" \
    trainer="vinod" \
    duration="120HRS"
# here user1 is key, someuser is default value
# we can overwrite this # docker build -t arg:1.0.0  --build-arg USERNAME=some-user . --> we need give like command to give run time variable
ARG USERNAME=vinod
ENV USERNAME=$USERNAME
RUN echo "Hello user: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]