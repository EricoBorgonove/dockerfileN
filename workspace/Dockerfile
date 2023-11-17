# Usar a imagem base do Debian ou Ubuntu
FROM debian:stable-slim

# Instalar ferramentas básicas
RUN apt-get update && apt-get install -y \
    curl \
    nano \
    git \
    && rm -rf /var/lib/apt/lists/*

# Definir o diretório de trabalho
WORKDIR /var/www

# Comando padrão ou ponto de entrada
CMD ["/bin/bash"]


