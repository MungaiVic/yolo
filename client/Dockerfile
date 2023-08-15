# Stage 1: Build environment
FROM node:14 AS build
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build

# Stage 2: Runtime environment
FROM node:14-alpine
WORKDIR /app
COPY --from=build /app/build ./build
EXPOSE 3000
CMD ["npm", "start"]
