FROM node:16.3.0

WORKDIR /app

COPY package.json ./
RUN npm install

COPY . .
EXPOSE 3000 
# Start react app
CMD ["npm", "start"]
