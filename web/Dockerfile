FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.config
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY dafault.conf /etc/nginx/nginx/nginx.conf
ADD static /usr/share/nginx/html
ENV CATALOGUE_HOST="catalogue"