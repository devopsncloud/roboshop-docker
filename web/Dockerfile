FROM  nginx 
RUN rm -rf /usr/share/nginx/html/index.html
COPY static /usr/share/nginx/html/
ADD roboshop.conf /etc/nginx/default.d/roboshop.conf    