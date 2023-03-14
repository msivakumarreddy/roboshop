FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/
ADD default.conf /etc/nginx/nginx.conf
ENV CATALOGUE_HOST="catalogue"