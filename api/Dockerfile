FROM node:12.13.0-alpine

WORKDIR /home/ec2-user/docker/api
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 3000

CMD ["npm", "run", "start"]
