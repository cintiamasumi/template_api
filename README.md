# Template API

A basic API template pre-configured with essential libraries and tools.

-Node
-Typescript
-Eslint
-CommitZeb
-Husky
-Jest
-SuperTest

---

## 📋 Prerequisites

- [Node.js](https://nodejs.org/) (versão 22.11 ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/) instalado

---

## 🚀 Getting Started

Follow these instructions to set up and run the project locally.

### Install dependencies

#### Run the following command to install all required dependencies:
    ```bash
    npm install  


Alternatively, you can use yarn:
    ```bash
    yarn install
    

        
#### Configure the environment variables

Create a .env file in the project's root directory. If you don't specify a PORT in the .env file, the default port will be set to 3000. Example:
    
    # Example .env file
    PORT=3000

#### Start the development server

Run the following command to start the server in development mode:

    npm run dev

Test the default route by accessing:

    
    GET http://localhost:3000/

