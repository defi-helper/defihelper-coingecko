FROM nginx:stable-alpine
WORKDIR /app
COPY deployments/dockerfiles/app/default.conf /etc/nginx/conf.d/default.conf
COPY deployments/dockerfiles/app/nginx.conf /etc/nginx/nginx.conf
EXPOSE 8080
