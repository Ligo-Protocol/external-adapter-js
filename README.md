# How to run

* Install dependencies
```
yarn

```

* Then run:

```
yarn start

```

* Get vehicleID from moralis(check below). On a different shell run:

```

curl -X POST -H "content-type:application/json" "http://localhost:8080/" --data '{ "id": 1, "data": { "vehicleId": "ad83323d-596b-4e0d-ad39-295bcbc92649" , "encToken": "zYPF6...vN4cx" } }'

```

# How to get vehicleID and encToken

* Run [frontend](https://github.com/Ligo-Protocol/chainlink-hackathon-2022-client) to get vehicleID in moralis.

* Get the encToken with:

```

curl https://ligo-node-4etzx.ondigitalocean.app/api/v0/smartcar/vehicles/<vehicle-id>/token

```

