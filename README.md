# automPostman

This project automates an API Collection from Postman using Newman

The framework contains the following 12 API calls for the website https://jsonplaceholder.typicode.com


1. GET: Filtrar las fotos según su ID.
2. GET: Filtrar usuario según su ID.
3. POST: Crear usuario.
4. DEL: Eliminar usuario según su ID.
5. GET: Todas las fotos.
6. GET: Filtrar las fotos según su ID.
7. POST: Crear registro de foto según su título.
8. DEL: Eliminar foto según su ID.
9. GET: Todos los albums.
10. GET: Filtrar album según su ID.
11. POST: Crear album.
12. DEL: Eliminar album según su ID.

# Tech Stack

* [Nodejs.](https://nodejs.org/en/about/)
* [Postman.](https://www.postman.com/)
* [Newman.](https://www.npmjs.com/package/newman)


# Before installing

* Node.js must be installed in order to run the project.
* Must run `npm install -g newman`.


# Installation

* Clone the repository from Github.
`git clone https://github.com/cjga01/automPostman.git`

* Run the Postman collection with the following command
`npm run newman` an HTML will be generated wit the test results