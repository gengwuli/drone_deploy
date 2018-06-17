from node:alpine 
WORKDIR /usr/local/app
ADD package.json /usr/local/app
ADD index.js /usr/local/app
RUN npm install
EXPOSE 3000
CMD ["node", "index.js"]
