#How to install Python 3.6.2

```
sudo yum -y update
sudo yum -y groupinstall "Development tools"
sudo yum -y install zlib-devel xz-libs zlib zlib-devel

cd /usr/local/lib
sudo wget https://www.python.org/ftp/python/3.6.2/Python-3.6.2.tar.xz
sudo xz -d Python-3.6.2.tar.xz
sudo tar -xvf Python-3.6.2.tar
cd Python-3.6.2
sudo ./configure
sudo make
sudo make altinstall

python3.6 --version
```
