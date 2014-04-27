# pound HTML error-pages
simple HTML error-pages for pound supportet error files

## setup
- copy the error-pages/ directory to the pound configuration directory (/etc/pound)
- add the following content into the ListenHTTP or ListenHTTPS statement
```
	# error-pages
	Err414 "/etc/pound/error-pages/414.min.html"
	Err500 "/etc/pound/error-pages/500.min.html"
	Err501 "/etc/pound/error-pages/501.min.html"
	Err503 "/etc/pound/error-pages/503.min.html"
```
