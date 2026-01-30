# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full stack open course

Fork the repository to complete course exercises

## Commands

Run docker container with Node 22, mount repository and expose required port 8080

`docker run -it --rm -v "c:\Users\mweissen\OneDrive - Capgemini\Desktop\repositories\full-stack-open-pokedex:/app" -w /app -p 8080:8080 --entrypoint sh node:22-bookworm`

Start by running `npm install` inside the project folder

`npm start` to run the webpack dev server
`npm test` to run tests
`npm run eslint` to run eslint
`npm run build` to make a production build
`npm run start-prod` to run your production build
