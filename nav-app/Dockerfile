# Build stage

FROM node:latest 

WORKDIR /nav-app/

# copy over needed files
COPY . ./

# install packages and build 
RUN npm install --unsafe-perm

EXPOSE 80

CMD npm start