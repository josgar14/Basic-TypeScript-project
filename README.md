This is a basic TypeScript project created using PARCEL bundler and json-server.

In order to run this project run the following commands:

npm install

npx parcel src/*.html // this command will run the parcel server and provide a url for local access. Run this command in a separate terminal.

npx json-server --watch db.json // This will run the json-server. Run this command in a separate terminal.

tsc src/ts/index.ts -w // compiles the TypeScript file. Run this command in a separate terminal.
