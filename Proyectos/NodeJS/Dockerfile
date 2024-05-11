#USAR: <IMAGEN>:<TAG>
FROM node:12.22.1-alpine3.11
#DIRECTORIODEFAULT: <UBICACION>
WORKDIR /app
#COPIAR <ORIGEN> <DESTINO>
COPY . .
#EJECUTAR <COMANDO> <>
RUN yarn install --production
#
CMD ["node", "/app/src/index.js"]
