FROM nginx:stable

RUN rm /etc/nginx/conf.d/default.conf
COPY backend.conf /etc/nginx/conf.d/backend.conf

EXPOSE 80 443