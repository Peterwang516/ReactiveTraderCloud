FROM        node:8
MAINTAINER  weareadaptive <thibault@weareadaptive.com>

RUN         mkdir -p /client
COPY client /client
#WORKDIR     /client

# COPY        client/package.json ./client
WORKDIR     /client
RUN         npm install


CMD         ["npm", "run", "build"]

# ENTRYPOINT  npm install && npm test && npm run deploy:prod
