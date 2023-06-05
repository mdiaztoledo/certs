# Openssl SelfSigned Certs

## Generating a self signed certificate
```
openssl req -newkey rsa:4096 \
            -x509 \
            -sha256 \
            -days 3650 \
            -nodes \
            -out example.crt \
            -keyout example.key
```

## One line version
```
openssl req -newkey rsa:4096 -x509 -sha256 -days 3650 -nodes -out example.crt -keyout example.key
```
