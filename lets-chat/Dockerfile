FROM node:17.2.0
# ENV NODE_ENV=production

WORKDIR /app
ADD . /app
EXPOSE 5000

RUN npm install

#COPY . .

CMD [ "npm", "start" ]
