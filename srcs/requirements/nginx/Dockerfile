# Utiliser l'image officielle Nginx comme base
FROM nginx:latest

COPY conf /etc/nginx/nginx.conf

COPY ./../../../secrets/nginx.crt /etc/nginx/ssl/nginx.crt
COPY ./../../../secrets/nginx.key /etc/nginx/ssl/nginx.key

COPY index.html /usr/share/nginx/html

# Exposer le port 443
EXPOSE 443

# Démarrer Nginx dans le conteneur
CMD ["nginx", "-g", "daemon off;"]
