FROM nodejs/nodejs
FROM caddy
EXPOSE 80
EXPOSE 443
COPY Caddyfile /etc/caddy/Caddyfile
COPY ./app /tmp
WORKDIR /tmp/app