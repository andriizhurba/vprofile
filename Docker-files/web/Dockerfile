FROM nginx:1.27.5
LABEL "Project"="Vprofile"
LABEL "Author"="Andrii"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/nginvproapp.conf

EXPOSE 80