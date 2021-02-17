# s5.go
Socks5 proxy server by golang
https://github.com/ring04h/s5.go

reference: shadowsocks go local.go
https://github.com/shadowsocks/shadowsocks-go
 
# Usage
```
$ go build s5.go
```

```
$ ./s5 -h
Usage of ./s5:
  -addr string
    	proxy listen address (default ":8080")
  -v	should every proxy request be logged to stdout
```
   
```
$ ./s5 -addr 127.0.0.1:2080 -v
2016/10/23 17:18:40 Listening 127.0.0.1:2080
```
