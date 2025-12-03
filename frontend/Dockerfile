FROM nginx:alpine 
# Copier les fichiers statiques dans le répertoire par défaut de Nginx
COPY index.html /usr/share/nginx/html/
COPY style.css /usr/share/nginx/html/

# Exposer le port HTTP standard
EXPOSE 80

# Commande par défaut (déjà définie dans l'image nginx:alpine)
# CMD ["nginx", "-g", "daemon off;"]
