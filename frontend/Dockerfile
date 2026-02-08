#redundant FROM but safer copy
FROM node:25
WORKDIR /frontend
COPY . /frontend/
RUN npm install
#gpt explains: run dev is not something done at build time
#front end vite has some complaints about usig host to expose port
CMD ["npm", "run", "dev", "--", "--host"]
EXPOSE 8080
#end of file
