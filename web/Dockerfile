FROM nginx
# Remove the default Nginx configuration file
RUN rm -v /etc/nginx/nginx.conf

# Copy a configuration file from the current directory
ADD nginx.conf /etc/nginx/
ADD index.html /usr/share/nginx/html
ADD /css /usr/share/nginx/html/css
