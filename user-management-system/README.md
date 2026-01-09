# User Management System

## Description
Système complet de gestion d'utilisateurs avec Spring Boot et Angular.

## Fonctionnalités
- Authentification JWT
- OAuth2 avec Google
- Gestion des rôles (USER/ADMIN)
- Interface Angular Material
- Docker & Kubernetes
- CI/CD avec GitHub Actions

## Installation
```bash
# 1. Cloner le projet
git clone https://github.com/username/user-management.git
cd user-management

# 2. Configurer l'environnement
cp .env.example .env
# Éditer .env avec vos valeurs

# 3. Démarrer avec Docker
make build
make up
