# This is the base OS  #dockerfile reference --> reference
FROM almalinux:9 
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
copy index.html /usr/share/nginx/html/index.html
# nginx command to start in container --> docker community forums
CMD  ["nginx", "-g", "daemon off;"]