FROM nginx:latest

COPY indexapp.html /usr/share/nginx/html/index.html
COPY indexwww.html /usr/share/nginx/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]