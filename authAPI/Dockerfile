FROM node
WORKDIR /home/app
COPY *.js /home/app/
COPY package*.json /home/app/
RUN npm install
EXPOSE 3000
ENV NODE_ENV=production
CMD node index.js


