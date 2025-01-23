FROM node:latest

WORKDIR /app

COPY package.json .

RUN npm install @siemens/ix @siemens/ix-react @siemens/ix-icons
RUN npm install

COPY . .


CMD [ "npm", "run", "dev" ]

