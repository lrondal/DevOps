FROM httpd:2.4-alpine

# Copy the confioguration
COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf

# Copy staticpage (won't be use when apache work)
COPY ./index.html /usr/local/apache2/htdocs/
