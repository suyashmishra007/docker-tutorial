FROM node

WORKDIR /app

# COPY [host file system] [image/container file system => /app] 
COPY . /app

RUN npm install

EXPOSE 8000

CMD ["node", "server.js"]

# docker build .
# docker run -p 3000:8000 3f7574f
#docker stop <containerName>