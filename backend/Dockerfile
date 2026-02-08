#redundant FROM from but safer copy
FROM node:25
WORKDIR /backend
COPY . /backend/
RUN npm audit fix && npm install && npm start
#end of file
