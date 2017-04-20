```bash
cd /usr/src
sudo wget https://www.openssl.org/source/openssl-1.1.0e.tar.gz
sudo tar -zxf openssl-1.1.0e.tar.gz
cd openssl-1.1.0e
sudo ./config
sudo make
sudo make test
#Just ignore error
sudo make install
sudo cp libssl.so.1.1 /usr/lib64
sudo cp libcrypto.so.1.1 /usr/lib64
openssl version
#OpenSSL 1.1.0e  16 Feb 2017
```
