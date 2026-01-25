# Usa uma imagem base com servidor web Apache
FROM nginx:alpine

# Remove configuração padrão do nginx
RUN rm /etc/nginx/conf.d/default.conf

# Copia seu site para dentro do container
COPY index.html /usr/share/nginx/html/index.html

# Expõe a porta 80
EXPOSE 80
