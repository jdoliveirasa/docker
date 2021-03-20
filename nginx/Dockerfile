FROM nginx:latest

COPY ./ /usr/share/nginx/html

ENTRYPOINT ["/docker-entrypoint.sh"]
CMD ["nginx", "-g", "daemon off;"]

#FROM ubuntu:latest

#ENTRYPOINT [ "echo", "Hello" ]

#CMD [ "World" ]