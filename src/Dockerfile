FROM node:14.17.5
EXPOSE 8181
WORKDIR /src
COPY ["src/package.json", "src/package-lock.json*", "./"]
RUN npm install
RUN npm install express
COPY src/. .
CMD [ "node","server.js" ]
