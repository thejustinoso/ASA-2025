FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
COPY proxy.conf /etc/nginx/proxy.conf

EXPOSE 80