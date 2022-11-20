FROM nginx:1.21.6
COPY nginx.conf /etc/nginx/nginx.conf
EXPOSE 80/tcp
EXPOSE 443/tcp
CMD ["/bin/sh", "-c", "exec nginx -g 'daemon off;';"]