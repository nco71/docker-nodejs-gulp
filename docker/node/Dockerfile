FROM node:alpine

#RUN apk add --update \

    # Install common packages
#	vim \
#        && \

    # Install nodejs specific packages
#    apk add --update \
#        nodejs && \

   # Install packages
#   apk add --no-cache bash && \

   # Install nodejs extensions

    # Define Git global config
    #git config --global user.name "Administrator" && \
    #git config --global user.email "admin@wodby.com" && \
    #git config --global push.default current && \

 # Fix permissions
RUN chmod 755 /root && \

# Create user www-data
adduser -D -s /bin/bash -u 82 www-data && \

mkdir -p /usr/src/app

WORKDIR /usr/src/app

RUN chown -R www-data:www-data /usr/src/app && \

npm install gulp -g && \ 

npm install



# C
#  mkdir -p /var/www/html && \
#  chown -R www-data:www-data /var/www

#  npm init 

#  npm install 

#WORKDIR /var/www/html

    # Final cleanup
#RUN  rm -rf /var/cache/apk/* /tmp/* /usr/share/man


#COPY docker-entrypoint.sh /usr/local/bin/
#CMD docker-entrypoint.sh



