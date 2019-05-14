FROM node:8

RUN apt install -y git
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

RUN git clone https://github.com/Dobloq/apius_web.git .
WORKDIR /usr/src/app/api-us
RUN ls
RUN npm install --quiet
 
EXPOSE 3080
CMD ["node", "index.js"]
