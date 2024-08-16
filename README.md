# API Documentation

## Descripción General

Esta API ofrece autenticación de usuarios mediante JSON Web Tokens (JWT) y cifrado de contraseñas utilizando Bcrypt. Permite a los usuarios crear, visualizar, modificar y eliminar sus perfiles, así como crear, ver, modificar y eliminar publicaciones. Además, los usuarios pueden marcar publicaciones como favoritas.

## Tecnologías Utilizadas

- Node.js
- Express
- Sequelize
- Bcrypt
- JSON Web Tokens (JWT)
- PostgreSQL

## Autenticación
Puedes generar tu `TOKEN_SECRET` con el comando de Node:
* require('crypto').randomBytes(64).toString('hex')
