FROM node:16.0.0
WORKDIR /app
COPY ./annotation-tool-frontend/dashboard/package.json  /app/
COPY ./annotation-tool-frontend/dashboard/package-lock.json  /app/
RUN npm install
RUN npm update --force
COPY ./annotation-tool-frontend/dashboard/ /app/
ENV SKIP_PREFLIGHT_CHECK=true
CMD ["npm", "start", "--port", "8002"]