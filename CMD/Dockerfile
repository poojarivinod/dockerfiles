# This is the base OS  #dockerfile reference --> reference
FROM almalinux:9 
RUN dnf install nginx -y
# nginx command to start in container --> docker community forums
# "daemon off" is a command used with programs like Nginx and other web servers to instruct them to run in the foreground, not the background
CMD  ["nginx", "-g", "daemon off;"] 
