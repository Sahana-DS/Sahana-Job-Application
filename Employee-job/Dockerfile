# Use a base image
FROM nginx:latest

# Copy your app to the container
COPY ./ /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Default command to run Nginx
CMD ["nginx", "-g", "daemon off;"]

