FROM node:14-alpine AS todofrontend
WORKDIR /frontend
ADD node_modules.tar.gz /backend/
COPY . .  
EXPOSE 3000
CMD ["npm", "start"]

