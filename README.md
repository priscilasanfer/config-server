# Config Server

### Encryption and Decryption

```curl
curl --location --request POST 'https://ead-configserver-ps.herokuapp.com/encrypt' \
--header 'Authorization: Basic XXXXXXXXXX' \
--header 'Content-Type: text/plain' \
--data-raw 'TEXTO'

```
