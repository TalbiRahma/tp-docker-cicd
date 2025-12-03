FROM node:18-alpine 

WORKDIR /app # Répertoire de travail dans le conteneur

# Optimisation du cache Docker : copier d'abord les dépendances
COPY package*.json ./
RUN npm install # Installe les dépendances dans node_modules

# Copier le reste du code source
COPY . .

EXPOSE 3000 

CMD ["npm", "start"] # Commande de démarrage par défaut
