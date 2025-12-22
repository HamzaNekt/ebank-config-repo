# eBank Config Repository

Ce dépôt contient les configurations externalisées pour l'application eBank (architecture microservices).

## Structure

- `application.yml` : Configuration globale (tous les microservices)
- `customer-service.yml` : Configuration du microservice Customer
- `account-service.yml` : Configuration du microservice Account
- `front-api-service.yml` : Configuration du microservice Front-API
- `gateway-service.yml` : Configuration de la Gateway

## Utilisation

Ce dépôt est utilisé par le **Spring Cloud Config Server** pour centraliser les configurations.

## Variables d'environnement

Certaines propriétés sensibles doivent être définies via des variables d'environnement :
- `JWT_SECRET` : Clé secrète pour JWT
- `MAIL_USERNAME` : Email pour l'envoi de notifications
- `MAIL_PASSWORD` : Mot de passe email
