FROM node:12.18.3
WORKDIR '/web'

COPY package.json .
RUN npm install
COPY . .
CMD ["npm", "start"]