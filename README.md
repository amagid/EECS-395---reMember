# Senior Project: reMember

App to help people easily remember the names and faces of people they meet.

### Setup Instructions
1) Make sure node.js and npm are installed. You can use "node -v" and "npm -v" to quickly check this. If you see semvers, you're good.
2) Navigate to the project directory in your console and type "npm install".
3) Navigate to the "config" folder. Copy the "development.json.sample" file twice. Name one "development.json" and the other "production.json".
4) Navigate to the "keys" folder. Use a tool like PuttyGen to generate an RSA key pair. Store keys in "jwt-public.key" and "jwt-private.key".
5) Navigate back to the root directory of the project and create a folder called "logs". Inside that, create a folder called "exceptions".
6) Navigate to the project directory in your console and type "npm run start" to make sure it works.
7) Navigate to the project directory in your console and type "npm test" to make sure it works.
