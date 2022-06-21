FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
COPY ./docker_setup/nginx/default.conf /etc/nginx/conf.d/
CMD ["nginx", "-g", "daemon off;"]