FROM node:18.13.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]

#Tomei a liberdade de fixar a versão do node para uma versão mais atual (diferente da mostrada na aula). Mas fiz os testes e aparentemente funcionou
