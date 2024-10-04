# CA
Howto install
copy CA.pl to path whilst renameing CA 
see  etc/tls/openssl.cnf
note: always work from $HOME

Howto create a new Certificate Authority
1. CA -newca
2. delete req
3. convert cacert.pem - cacert.cer

important: never disclose private/cakey.pem

Howto Revoke
1. CA -revoke demoCA/cacert.pem unspecified

Howto install CA certificate
1. import cacert.cer
or use mk-ca-bundle
