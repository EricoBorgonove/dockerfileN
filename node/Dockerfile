# Usar a imagem oficial do Node.js
FROM node:16-slim

# Definir o diretório de trabalho no container
WORKDIR /var/www

# Copiar os arquivos package.json e package-lock.json (se disponível)
COPY package*.json ./

# Instalar as dependências do projeto
RUN npm install

# Copiar os arquivos do projeto para o diretório de trabalho
COPY . .

# Expor a porta que a aplicação vai rodar
EXPOSE 3000

# Comando para rodar a aplicação
CMD ["npm", "start"]




