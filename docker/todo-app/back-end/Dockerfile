FROM node:16.20.1-alpine3.18
EXPOSE 3001
WORKDIR /app/back-end
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "start" ]