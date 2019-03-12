### the first section is necessary for both assignments

FROM node:10

WORKDIR usr/src/app

COPY package*.json ./

RUN npm i

### only uncomment the code for the hw assignment you're grading

### Liri HW ###

# COPY . .

# RUN ls
# RUN node liri.js concert-this metallica
# RUN node liri.js spotify-this-song enter sandman
# RUN node liri.js movie-this Serendipity
# RUN node liri.js do-what-it-says
# RUN node liri.js help

### End Liri HW ###

### Bamazon HW ###
### CMD's second argument should be the customer file

# CMD ["node", "bamazoncustomer.js"]
CMD ["node", "server.js"]

### end Bamazon HW ###