FROM 192.168.177.248/nginx/nginx:v190707
COPY ./server.key /etc/nginx
COPY ./server.pem /etc/nginx
COPY ./*.conf /etc/nginx/conf.d
CMD ["nginx","-g","daemon off;"]
EXPOSE 443
