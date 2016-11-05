FROM nginx

MAINTAINER m3philis <github.com/m3philis>

ADD ./conf.d /etc/nginx/conf.d
ADD ./content /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off;"]
