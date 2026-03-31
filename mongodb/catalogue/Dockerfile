FROM node:20
WORKDIR /app
COPY package*.json ./
COPY *.js ./
RUN npm install
CMD ["node", "server.js"]
ENV MONGO="true" \
    MONGO_URL="mongodb://mongodb:27017/catalogue" 