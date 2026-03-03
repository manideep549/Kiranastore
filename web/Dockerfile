FROM nginx:alpine
COPY . /usr/share/nginx/html
# Add this line to give read permissions
RUN chmod -R 755 /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]