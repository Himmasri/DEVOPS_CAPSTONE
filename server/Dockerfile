FROM node:18
WORKDIR /DEVOPS_CAPSTONE
COPY package*.json ./
RUN npm install
COPY . .
CMD ["node","index.js"]