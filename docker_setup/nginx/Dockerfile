
FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
COPY ./docker/nginx/default.conf /etc/nginx/conf.d/
CMD ["nginx", "-g", "daemon off;"]