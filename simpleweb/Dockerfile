# base image
FROM node:alpine

# working dir
WORKDIR /usr/app

# add local files
COPY ./package.json ./

# dependancies
RUN npm install

# add the rest of the local files
COPY ./ ./

# default command
CMD ["npm", "start"]