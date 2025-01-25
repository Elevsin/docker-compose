FROM node:16
COPY ./react-app-Elevsin ./client
WORKDIR /client/
EXPOSE 3000
RUN npm install && npm run build
CMD ["npm", "start"]
