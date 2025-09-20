# This is the base OS  #dockerfile reference --> reference
FROM almalinux:9 
RUN dnf install nginx -y
#there is no functionality for EXPOSE, it is just for information
EXPOSE 80
# nginx command to start in container --> docker community forums
CMD  ["nginx", "-g", "daemon off;"]