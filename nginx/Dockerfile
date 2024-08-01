FROM nginx:1.21.3-alpine

# COPY ./nginx/certs /etc/nginx/certs/
COPY ./nginx/default.conf /etc/nginx/conf.d/

COPY start.sh ~/

RUN chmod +x ~/start.sh

CMD ~/start.sh
