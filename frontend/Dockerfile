FROM node:13.8.0-stretch AS build
WORKDIR /
COPY package.json ./
# COPY . .

RUN npm install
RUN npm run build

# FROM nginx
# COPY nginx.conf /etc/nginx/conf.d/default.conf
# COPY --from=build /dist /usr/share/nginx/html
# EXPOSE 80
