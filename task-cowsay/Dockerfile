   FROM node:18-slim
   WORKDIR /app
   COPY package.json app.js ./
   RUN npm install --only=production
   CMD ["npm", "start"]