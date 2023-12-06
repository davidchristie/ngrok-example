# Ngrok Example

A quick example of how to deploy services using [ngrok](https://ngrok.com/).

## Usage

1. Create a free [ngrok](https://ngrok.com/) account.
2. Create a .env file at the root of the project and add the ngrok auth token:
```
NGROK_AUTHTOKEN="*****"
```
3. Start the docker services:
```
docker compose up -d
```
4. Open <http://localhost:4040> to view the ngrok UI. It lists the public URLs of the deployed services (Foo and Bar).
