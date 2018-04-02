FROM nginx:alpine

RUN touch /var/run/nginx.pid && mkdir /var/cache/nginx/client_temp && chown -R 1001:0 /var/cache/nginx /var/run/nginx.pid

USER 1001
