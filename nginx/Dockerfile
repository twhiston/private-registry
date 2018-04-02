FROM nginx:alpine

RUN touch /var/run/nginx.pid chmod -R 0664 /var/cache/nginx && chown -R 1001:0 /var/cache/nginx /var/run/nginx.pid

USER 1001
