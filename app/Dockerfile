FROM node

RUN npm i -g serve

COPY html /src/html/

WORKDIR /src/

RUN cd /src/

CMD [ "serve", "-s", "html" ]
