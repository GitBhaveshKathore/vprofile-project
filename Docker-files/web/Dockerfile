FROM nginx
LABEL "Project"="Vrofile"
LABEL "Author"="Bhavesh"

RUN rf -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
