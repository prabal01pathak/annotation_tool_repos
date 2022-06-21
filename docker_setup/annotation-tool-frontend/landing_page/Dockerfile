FROM node:16.0.0
WORKDIR /app
COPY ./annotation-tool-frontend/landing_page/package.json /app/
COPY ./annotation-tool-frontend/landing_page/package-lock.json /app/
RUN npm i
COPY ./annotation-tool-frontend/landing_page/ /app/
CMD ["npm", "start"]