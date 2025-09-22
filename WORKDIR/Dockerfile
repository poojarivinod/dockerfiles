FROM almalinux:9
RUN mkdir /tmp/work-dir-demo
WORKDIR /tmp/work-dir-demo
RUN pwd
#"Hello from work dir" store in  hello.text file in the /tmp/work-dir-demo folder
RUN echo "Hello from work dir" > hello.text
CMD ["sleep", "100"]