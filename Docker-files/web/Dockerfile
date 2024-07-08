FROM nginx
LABEL "Project"="Vprofile"
LABEL "Author"="MinPyae"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx_vproapp.conf /etc/nginx/conf.d/vproapp.conf