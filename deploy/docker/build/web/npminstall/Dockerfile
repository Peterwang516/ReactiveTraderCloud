FROM        __NODE_CONTAINER__
MAINTAINER  weareadaptive <thibault@weareadaptive.com>

COPY        client /client

WORKDIR     /client

RUN         npm install

ENTRYPOINT  ["npm", "run", "build"]

# ENTRYPOINT  npm install && npm test && npm run deploy:prod
