# FastCGIpy

A standalone FastCGI client in Python 3

Usage: 

```
python3 fcgi_client.py <SCRIPT_FILENAME> <STDIN>
python3 fcgi_client.py /bin/cgi.sh ""
```

License: MIT

Url: https://github.com/monperrus/FastCGIpy

Notes:

* Fork from https://github.com/pquentin/flup-py3/blob/master/flup/client/fcgi_app.py, without any WSGI
* FastCGI Specification: https://fastcgi-archives.github.io/FastCGI_Specification.html (29 April 1996)
* nginx fastcgi module: http://nginx.org/en/docs/http/ngx_http_fastcgi_module.html
* Similar repositories
  - https://github.com/wuyunfeng/Python-FastCGI-Client in Python
  - https://github.com/yookoala/gofast/blob/main/fcgi.go in Go
  - https://github.com/hollodotme/fast-cgi-client in PHP
  - https://www.npmjs.com/package/fastcgi-client in Javascript
  - https://crates.io/crates/fastcgi-client in Rust
