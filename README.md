## GraphQL Hello World (English)
Description
This project is a basic GraphQL server implemented using Node.js and Express. It includes a simple "Hello World" query that responds with a greeting message, ideal for understanding the fundamental concepts of GraphQL. The project also includes Docker support for containerization.

Technologies Used
Node.js: v18.x or higher
GraphQL: v16.9.0
Express: v4.18.0
Express-GraphQL: v0.12.0
Docker: Latest
Requirements
To run this project, you need:

Node.js and npm installed. (Download Node.js)
Docker installed. (Download Docker)
Git installed.
Steps to Clone the Project
Run the following command to clone the repository:

```bash
git clone <repository-url>
cd graphql-hello-world
```
Install and Run Locally
Install dependencies:

```bash
npm install
```
Start the GraphQL server:

```bash
node src/server.js
```
Access the GraphQL Playground by visiting:

```bash
http://localhost:4000/graphql
```
Run the Project with Docker
Build the Docker image:

```bash
docker build -t graphql-hello-world .
```
Run the container:

bash
Copiar código
docker run -p 4000:4000 graphql-hello-world
Access the GraphQL Playground at:

```bash
http://localhost:4000/graphql
```
Docker Hub Link
You can pull the pre-built image from Docker Hub here:
Docker Hub Repository

## GraphQL Hello World (Español)
Descripción
Este proyecto es un servidor GraphQL básico implementado usando Node.js y Express. Incluye una consulta simple "Hello World" que devuelve un mensaje de saludo, ideal para entender los conceptos fundamentales de GraphQL. El proyecto también incluye soporte para Docker.

Tecnologías Utilizadas
Node.js: v18.x o superior
GraphQL: v16.9.0
Express: v4.18.0
Express-GraphQL: v0.12.0
Docker: Última versión
Requisitos
Para ejecutar este proyecto, necesitas:

Node.js y npm instalados. (Descargar Node.js)
Docker instalado. (Descargar Docker)
Git instalado.
Pasos para Clonar el Proyecto
Ejecuta el siguiente comando para clonar el repositorio:

```bash
git clone <repository-url>
cd graphql-hello-world
```
Instalar y Ejecutar Localmente
Instalar dependencias:

```bash
npm install
```
Iniciar el servidor GraphQL:

```bash
node src/server.js
```
Acceder a GraphQL Playground visitando:

```bash
http://localhost:4000/graphql
```
Ejecutar el Proyecto con Docker
Construir la imagen Docker:

```bash
docker build -t graphql-hello-world .
```
Ejecutar el contenedor:

```bash
docker run -p 4000:4000 graphql-hello-world
```
Acceder a GraphQL Playground en:

```bash
http://localhost:4000/graphql
```
Enlace de Docker Hub
Puedes descargar la imagen pre-construida desde Docker Hub aquí:
Repositorio Docker Hub
