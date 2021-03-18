    
<p align="center">
<img src="https://github.com/Luksdantas/ReactJS-Happy/blob/main/src/images/landing.svg" />
</p>

<h1 align="center">:smile: Happy :smile:</h1>
<p align="center">Happy a way to help kids!</p>

<p align="center">
 <img  src="https://img.shields.io/github/package-json/dependency-version/Luksdantas/NodeJS-Happy/express" alt="Express Version">
 <img  src="https://img.shields.io/github/package-json/dependency-version/Luksdantas/NodeJS-Happy/express-async-errors" alt="Express async erros Version">
  <img  src="https://img.shields.io/github/package-json/dependency-version/Luksdantas/NodeJS-Happy/cors" alt="Cors Version">
   <img  src="https://img.shields.io/github/package-json/dependency-version/Luksdantas/NodeJS-Happy/multer" alt="multer Version">
    <img  src="https://img.shields.io/github/package-json/dependency-version/Luksdantas/NodeJS-Happy/sqlite3" alt="sqlite3 Version">
        <img  src="https://img.shields.io/github/package-json/dependency-version/Luksdantas/NodeJS-Happy/typeorm" alt="typeorm Version">
            <img  src="https://img.shields.io/github/package-json/dependency-version/Luksdantas/NodeJS-Happy/yup" alt="yup Version">
 <img  src="https://img.shields.io/github/package-json/dependency-version/Luksdantas/NodeJS-Happy/dev/typescript" alt="Typescript Version">
</p>

<h1>:memo:About</h1>
<p>Happy is a project developed during the <a href="https://nextlevelweek.com/">Next Level Week 3</a> presented by <a href="https://www.linkedin.com/school/rocketseat/">Rockeseat</a>. This project is a way to help kids who lives in Orphanages.</p>
<p>Web: <a href="https://github.com/Luksdantas/ReactJS-Happy">Happy Web</a></p>
<p>Mobile: <a href="https://github.com/Luksdantas/ReactNative-Happy">Happy Mobile</a></p>



<h1>:rocket: Getting started</h1>

```bash

# Clone this repository
$ git clone https://github.com/Luksdantas/NodeJS-Happy.git

# Access the project folder cmd/terminal
$ cd NodeJS-Happy

# install the dependencies
$ npm install

# Run the application in development mode
$ npm run dev

# The application will open on the port: 3333 - go to http://localhost:3333

```

h1>🛠 DevRadar API</h1>

<h2>POST Create Orphanage</h2>
<h3>Request</h3>

`POST /orphanages`

```

```

<h3>Response</h3>

```
```

<h2>GET List Orphanages</h2>
<h3>Request</h3>

`GET /orphanages`
<h3>Response</h3>

```
[
  {
    "id": 1,
    "name": "Happy",
    "latitude": -3.780902067561049,
    "longitude": -38.54053694754839,
    "about": "Ajude lares para crianaças",
    "instructions": "Quando puder!",
    "opening_hours": "24 horas",
    "open_on_weekends": true,
    "images": [
      {
        "id": 1,
        "url": "http://localhost:3333/uploads/1616092014612-image_0.jpg"
      }
    ]
  }
]
```

<h2>GET Orphanage</h2>
<h3>Request</h3>

`GET /orphanages/:id`

<h3>Response</h3>

```
{
  "id": 1,
  "name": "Happy",
  "latitude": -3.780902067561049,
  "longitude": -38.54053694754839,
  "about": "Ajude lares para crianaças",
  "instructions": "Quando puder!",
  "opening_hours": "24 horas",
  "open_on_weekends": true,
  "images": [
    {
      "id": 1,
      "url": "http://localhost:3333/uploads/1616092014612-image_0.jpg"
    }
  ]
}
```


<h1>:bookmark_tabs: License</h1>
 <img  src="https://img.shields.io/github/license/Luksdantas/NodeJS-Happy" alt="License">
 
 <p>Made with :heart: by Lucas Dantas 👋🏽 <a href="https://www.linkedin.com/in/luksdantas/">Get in Touch!</a></p>
