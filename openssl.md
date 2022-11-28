# openssl

```bash

openssl s_client -connect github.com:443 -cipher ECDHE-RSA-AES128-SHA256 -tls1_2 -curves prime256v1

openssl ecparam -list_curves

openssl enc -aes-256-cbc -in infile -out outfile -pass pass:"Secret Passphrase" -e -base64

```