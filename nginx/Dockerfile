FROM nginx:latest
# Stage 2 - the staging environment
COPY nginx.conf /etc/nginx/nginx.conf

WORKDIR /usr/share/nginx/html

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
