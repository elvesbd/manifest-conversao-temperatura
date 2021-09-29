FROM node:14.17.5

WORKDIR /app

COPY package*.json ./

RUN yarn install

COPY  . .

EXPOSE 8080

CMD ["node", "server.js"]

# Nomeando imagem
# Namespace(a quem pertece)/repositorio(api-conversao)/tag(v1)
# elvesbd41/conversao-temperatura:v1

# usar sempre o .dockerignore