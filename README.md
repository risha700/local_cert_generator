# local_cert_generator MacOS - Linux
## generate root cert first:
follow: https://github.com/risha700/local-cert-generator
## directory structure
```
├── generate
├── rootCA.key # generated
├── rootCA.pem # generated
├── rootCA.srl # generated
├── server.csr.cnf
└── v3.ext
```
## Usage:
```
args: 
    optional:
        string domain
        number IP - defaults to current machine ip
example:
./generate "domain.com" IP.00.000.00

output:
    cert folder in current directory with server .key and .crt 
```
