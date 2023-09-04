# annualsaga-website
Annual Saga Website

## Bringing Up the Web Service

`docker compose up`

Force a rebuild: `docker compose up --build`

## Building a Distribution

### Compile the App

`docker exec -it annualsaga-website npm run build -- --output-path=dist/<custompath>`

Afterwards, upload the contents of the `dist` folder into the S3 Bucket

## Shutting Down

`docker compose down`
