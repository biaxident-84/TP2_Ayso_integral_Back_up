FROM nginx:latest
COPY web/ /usr/share/nginx/html/
EXPOSE 80
HEALTHCHECK --interval=30s CMD curl -f http://localhost/ || exit 1
