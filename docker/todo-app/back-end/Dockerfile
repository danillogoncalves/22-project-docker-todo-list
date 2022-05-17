FROM node:14.5.0-alpine
WORKDIR /app
EXPOSE 3001
ADD /node_modules.tar.gz ./
COPY . .
CMD ["npm", "start"]
