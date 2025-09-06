# Frontend Dockerfile
FROM nginx:alpine

# Copy your HTML/JS files into nginx's default html folder
COPY index.html /usr/share/nginx/html/index.html

# Expose nginx default port
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]
