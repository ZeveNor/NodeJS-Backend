# NodeJS-Backend Templates

NodeJS-Backend is a Node.js-based application designed for the start checkpoint of project with key dependencies such as Express, and PostgreSQL. This guide will walk you through setting up the project for development.

## Buy me a coffee.
![Avatar](https://discord.c99.nl/widget/theme-2/854433449539534858.png)

## Prerequisites

Ensure the following prerequisites are met before setting up the project:

- **Node.js** version: v20.17.0  
- **npm** (Node Package Manager)

If you do not have the required Node.js version, you can manage it using [nvm (Node Version Manager)](https://github.com/nvm-sh/nvm):

```
nvm install 20.17.0  
nvm use 20.17.0
```

## Installation

1. Clone the repository:  
  ```
  git clone https://github.com/ZeveNor/NodeJS-Backend.git 
  cd NodeJS-Backend
  ```
3. Install the required dependencies:  
  ```
  npm install
  ```
## Running in Development Mode

To run the project in development mode using nodemon:
```
nodemon index.js
```

## Required Dependencies

This project relies on the following npm packages:
----------------------------------------------------------------------------------
| Package   | Version        | Description                                       |
| --------- | -------------- | ------------------------------------------------- |
| dotenv    | ^16.4.5        | Loads environment variables from `.env` file      |
| express   | ^4.19.2        | Web framework for Node.js                         |
| nodemon   | ^3.1.7         | Auto-restarts Node.js server upon file changes    |
| pg        | ^8.12.0        | PostgreSQL client for Node.js                     |

----------------------------------------------------------------------------------

### Installing Dependencies

To install all required dependencies, run:

```
npm install dotenv@^16.4.5 express@^4.19.2 nodemon@^3.1.7 pg@^8.12.0
```

## Usage

Once all dependencies are installed, you can start the development server by running:

```
nvm use 20.17.0  
nodemon index.js
```

