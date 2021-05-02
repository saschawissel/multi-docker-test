FROM node:14.14.0-alpine
WORKDIR '/app'
COPY --chown=node:node ./package.json ./
RUN npm install
#RUN chown node:node /app/node_modules
COPY --chown=node:node . .
CMD ["npm", "run", "start"]