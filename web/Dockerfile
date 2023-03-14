FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN         rm -f /etc/nginx/conf.d/default.conf
ADD static /usr/share/nginx/html/
ADD default.conf /etc/nginx/nginx.conf
ENV CATALOGUE_HOST="catalogue"