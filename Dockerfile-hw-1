from node:16-alpine
workdir /frontend
copy . ./
copy ./public /frontend/public
copy ./src /frontend/src
run npm install
run npm run build
cmd ["npm", "start"]
