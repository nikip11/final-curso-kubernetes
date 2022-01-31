# Proyecto fin de curso

## Objetivo

Crear una infraestructura cons docker y kubernetes para desplegar un proyecto base de symfony

## Servicios necesarios
- php 8.0
- nginx
- mysql
- phpMyAdmin

### php
## Permisos azure

az aks update -n led-dev03 -g led-dev03 --attach-acr leddev03
docker pull leddev03.azurecr.io/final-curso-php:1.0
docker pull leddev03.azurecr.io/final-curso-nginx:1.0