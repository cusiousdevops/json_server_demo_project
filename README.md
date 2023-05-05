## How to setup json server locally

- you should have npm installed in your system

### Install json-server

- npm install -g json-server

### creating `db.json` file with some data to verify

```
{
   "students": [
    {"id": 101, "name": "shivam kumar", "class": 9},
    {"id": 102, "name": "rahul kumar", "class": 9},
    {"id": 103, "name": "rohit kumar", "class": 9}
  ]
}
```

### Now starting the json server

- json-server --watch db.json
