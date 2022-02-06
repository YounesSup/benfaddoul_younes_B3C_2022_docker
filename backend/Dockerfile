#image
FROM alpine

#Executer la commande mkdir -p /usr/src/app
RUN mkdir -p /usr/src/app

#Definir le repertoire de travail
WORKDIR /usr/src/app

#Copier ses fichiers dans l'image docker
COPY ./package.json ./
COPY ./yarn.lock ./

#Executer la commande npm install yarn
RUN npm install yarn

COPY . .

#Definir le port d'ecoute
EXPOSE 5000

#Commande par defaut lors de l'execution des containers
CMD ["yarn","start"]