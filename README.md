## Configure ngnix v1.10.3 with geoip2 

## prerequsites
```
sudo apt-get install -y build-essential
sudo apt-get install -y libpcre3-dev zlib1g-dev libssl-dev libxslt1-dev
sudo add-apt-repository -y ppa:maxmind/ppa
sudo apt-get update
sudo apt-get install -y libmaxminddb-dev
```

# steps
```
git clone https://github.com/StratoxEnterprises/ngx_http_geoip2_module.git
git clone https://github.com/StratoxEnterprises/nginx.git
```
```
git checkout tags/release-1.10.3
```
```
cd nginx/
```
```
./configure_me_better.sh
make
make install
```
