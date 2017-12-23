FROM mhart/alpine-node:latest
RUN mkdir -p /alc/belvinFolder/app
WORKDIR /alc/belvinFolder/app
COPY package.json /alc/belvinFolder/app
RUN npm install
COPY . /alc/belvinFolder/app
EXPOSE 3000
CMD ["npm","start"]