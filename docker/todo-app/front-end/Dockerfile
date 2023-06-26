FROM node:16.20.1-alpine3.18
EXPOSE 3000
WORKDIR /app/front-end
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "start" ]
