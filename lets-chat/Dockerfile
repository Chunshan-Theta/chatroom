FROM node:stretch-slim
# ENV NODE_ENV=production

WORKDIR /app
ADD . /app
EXPOSE 5000

RUN npm install --production

COPY . .

CMD [ "npm", "start" ]
