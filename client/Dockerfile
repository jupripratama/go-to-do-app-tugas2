# pull the official base image
FROM node:alpine
WORKDIR /app
COPY package.json ./
COPY package-lock.json ./
COPY ./ ./
RUN npm install react-scripts@2.1.8
RUN npm i

CMD ["npm", "run", "start"]