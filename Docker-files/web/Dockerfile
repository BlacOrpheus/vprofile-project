FROM nginx
LABEL "Project"="Vprofile"
LABEL "Author"="Imran"

# Fix the missing space in the rm command
RUN rm -rf /etc/nginx/conf.d/default.conf

# Ensure the nginvproapp.conf file exists in the build context
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
