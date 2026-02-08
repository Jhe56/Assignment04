#redundant FROM but safer copy
FROM node:25
WORKDIR /frontend
COPY . /frontend/
RUN npm install
EXPOSE 8080
#gpt explains: run dev is not something done at build time
CMD ["npm", "run", "dev"]
#end of file
