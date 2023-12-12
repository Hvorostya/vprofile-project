FROM nginx
LABEL "Project" = "VProfile"
LABEL "Author" = "I-Man"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf