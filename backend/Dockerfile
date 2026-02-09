#redundant FROM from but safer copy
FROM node:25
WORKDIR /backend
COPY . /backend/
RUN npm install
#gpt suggested fix to nodemon permission denied
RUN npm install -g nodemon

#gpt explained npm start isn't run at build time but meant for CMD
CMD ["npm", "start"]
#end of file
