Build backend project
mvn package

Build fontend project
npm install
export NODE_OPTIONS=--openssl-legacy-provider
npm run build

Build images and run containers
docker-compose up --build
