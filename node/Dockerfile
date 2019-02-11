FROM node:10

WORKDIR usr/src/app

COPY package*.json ./

RUN npm i

COPY . .

# RUN ls
RUN node liri.js concert-this metallica
RUN node liri.js spotify-this-song enter sandman
RUN node liri.js movie-this Serendipity
RUN node liri.js do-what-it-says
RUN node liri.js help

# CMD ["npm", "start"]
