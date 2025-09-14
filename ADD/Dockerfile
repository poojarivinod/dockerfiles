# This is the base OS  #dockerfile reference --> reference
FROM almalinux:9 
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# ADD command will copy the application from internet, but COPY command cannot do it 
ADD https://raw.githubusercontent.com/poojarivinod/dockerfiles/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html
# nginx command to start in container --> docker community forums
CMD  ["nginx", "-g", "daemon off;"]