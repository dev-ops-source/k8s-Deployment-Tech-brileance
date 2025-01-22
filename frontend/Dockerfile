FROM nginx:alpine
# Copy the contents of the build directory to the Nginx HTML directory
COPY dist/ElearningManagement  /usr/share/nginx/html
COPY default.conf /etc/nginx/conf.d/default.conf
CMD ["nginx", "-g", "daemon off;"]

