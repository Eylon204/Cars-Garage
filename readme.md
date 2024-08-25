# This program demonstarte working with Json Server
# Building thebacked:

## instal server:
npm install json-server

## Create a json file:
{
  "cars": [
    {
      "id": "97ea",
      "brand": "minicupper",
      "model": "Sport",
      "year": "2024",
      "color": "red",
      "price": "20000"
    }
  ]
}  

## Run The Server:
npx json-server db.json

# Result:
Index:
http://localhost:3000/

Static files:
Serving ./public directory if it exists

Endpoints:
http://localhost:3000/cars

# Building the Frontend
## install axios:
    <script src="https://cdn.jsdelivr.net/npm/axios@1.6.7/dist/axios.min.js"></script>

## CRUD
Get-Read
Put-Update
Post-Add new
Delete-Delete