
# poke_service

## Description

This project is a RESTful API developed with Node.js, Express, and Mongoose. It provides services to interact with data related to Pokémon.

## Installation

To get started with this project, follow these steps:

1. **Clone the repository:**

```bash
git clone https://github.com/1marincoh2/poke_service

2. **Navigate to the project directory:**

   cd poke_service

3. **Install dependencies:**

   npm install

## Usage
 *To run the development server:**

npm run start

## Endpoints

The API provides the following endpoints:

GET api/pokemon Get all Pokémon stored in the database.
GET api/pokemon/:id  Get a specific Pokémon by its ID.


POST /api/coach Crea un nuevo coach y lo guarda en la base de datos.
GET /api/coach Obtiene todos los coaches almacenados en la base de datos.
GET /api/coach/:id Obtiene un coach específico por su ID.
PUT /api/coach/  Actualiza la información de un coach específico por su ID.
DELETE /api/coach/:id Elimina un coach específico de la base de datos por su ID.


Configuration
The project uses the following core dependencies:

axios: HTTP client for making requests to other APIs.
cors: Middleware to enable CORS in Express.
dotenv: Load environment variables from a .env file.
express: Web application framework for Node.js.
mongoose-timestamp: Mongoose plugin that adds automatic timestamp fields to documents.
mongoose: MongoDB object modeling library for Node.js.
Additionally, nodemon is used as a development dependency to automatically restart the server when changes are made to the code.

Author
Name: José Alberto Marín Coh

License
This project is licensed under the ISC License. See the LICENSE file for more details.   
