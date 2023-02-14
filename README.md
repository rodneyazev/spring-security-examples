# spring-security-examples
You can test the authentication via curl, postman, insomnia, and browser.
At will to contact me if face any problem.

Keys generation (e.g.):

Folder to create the certificate files: /src/main/resources/certs

openssl.exe genrsa -out keypair.pem 2048

openssl.exe rsa -in keypair.pem -pubout -out public.pem

openssl.exe pkcs8 -topk8 -inform PEM -outform PEM -nocrypt -in keypair.pem -out private.pem

