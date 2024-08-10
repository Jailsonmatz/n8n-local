
FROM n8nio/n8n:latest

# Defina o diretório de trabalho
WORKDIR /home/node

RUN mkdir -p /home/node/.n8n 

# Expor a porta 5678 usada pelo n8n
EXPOSE 5678

# Comando para iniciar o n8n
CMD ["n8n"]
