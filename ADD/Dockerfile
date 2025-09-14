# This is the base OS  #dockerfile reference --> reference
FROM almalinux:9 
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# ADD command will copy the application from internet, but COPY command cannot do it 
ADD https://raw.githubusercontent.com/poojarivinod/dockerfiles/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html
# when we download application from internet, then we don't have permissions properly, so
RUN chmod +r /usr/share/nginx/html/index.html
# sample tar file download --> Sample tar Archive File Download --> sample-1.tar
# sample tar file is copied to tmp folder, while sample tar file coming to container, it will extract and copy it 
ADD sample-1.tar /tmp/
# nginx command to start in container --> docker community forums
CMD  ["nginx", "-g", "daemon off;"]