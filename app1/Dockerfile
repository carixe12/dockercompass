# Use a lightweight web server
FROM nginx:alpine

# Copy the HTML file to the nginx server
COPY index.html /usr/share/nginx/html/index.html
COPY app.js /usr/share/nginx/html/app.js

# Expose the default port
EXPOSE 80
