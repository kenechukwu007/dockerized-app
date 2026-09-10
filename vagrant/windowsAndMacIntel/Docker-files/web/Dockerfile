FROM nginx 
LABEL "Project"="vprofile-project"
LABEL "Author"="Kene"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginxvproapp.conf /etc/nginx/conf.d/vproapp.conf