# Use an official lightweight web server as the base image
FROM nginx:alpine

# Copy the web app files to the appropriate directory in the container
COPY . /usr/share/nginx/html

# Expose the default HTTP port
EXPOSE 80

# Command to start the web server
CMD ["nginx", "-g", "daemon off;"]
