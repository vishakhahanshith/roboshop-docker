FROM nginx
# Remove the default html in the below line
RUN rm -rf /usr/share/nginx/html/index.html
# Copy roboshop.conf to this directory in the below line
COPY roboshop.conf /etc/nginx/conf.d/roboshop.conf
# Similarly i need to copy the code also as below
ADD static /usr/share/nginx/html/