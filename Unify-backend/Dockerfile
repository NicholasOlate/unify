FROM node:15
WORKDIR /code
COPY . .
RUN npm install
RUN chmod +x ./wait-for-it.sh
CMD ["npx", "nodemon"]

