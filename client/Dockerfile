FROM node:16.13.0-alpine

# Create app directory
WORKDIR /client

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
COPY package*.json /client/

RUN npm install
# If you are building your code for production
# RUN npm ci --only=production

# Bundle app source
COPY . /client/

EXPOSE 3000
CMD [ "npm", "run", "start" ]