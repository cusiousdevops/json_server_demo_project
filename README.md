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
![image](https://user-images.githubusercontent.com/69252900/236375621-830e34d6-41e3-4efb-b14d-50d95da139aa.png)
![image](https://user-images.githubusercontent.com/69252900/236375673-d8a2167d-e6bc-4bbc-b50c-fb72a1cf7df8.png)
![image](https://user-images.githubusercontent.com/69252900/236375734-0447f2c3-4b32-4567-a878-1776cd6c441c.png)
![image](https://user-images.githubusercontent.com/69252900/236375765-73c86244-a732-4203-8f19-ac9343d95411.png)

