FROM nginx:alpine

RUN touch /var/run/nginx.pid && chown -R 1001:nginx /var/cache/nginx /var/run/nginx.pid

USER 1001
