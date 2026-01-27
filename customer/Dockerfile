FROM node

WORKDIR /app/customer

COPY package.json .

RUN npm install

COPY . .

LABEL test-change="true"


EXPOSE 8001

CMD ["npm", "start"]