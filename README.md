# Descripción del proyecto

## Levantar proyecto en dev

1. Clonar el repositorio
2. Crear una copia del archivo `.env.template` y renombrarlo a `.env`
3. Ajustar las variables de entorno en el archivo `.env`
4. Instalar dependencias `npm install`
5. Levantat la base de datos `docker-compose up -d`
6. Ejecutar seed de la base de datos `npm run seed`
7. Correr las migraciones de Proisma `npx prisma migrate dev`
8. Levantar el proyecto `npm run dev`

## Levantar proyecto en prod
