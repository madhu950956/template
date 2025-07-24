FROM nginx:latest
LABEL name="Sam" version="v1.0.0"
WORKDIR /usr/share/nginx/html
RUN rm -rf ./*
COPY . /usr/share/nginx/html/
EXPOSE 80
