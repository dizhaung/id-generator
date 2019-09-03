### Usage
```
Usage: id-generator [-hv] [-c config file] [-d data center id] [-w worker id] [-p port] [-r router]
  -c string
Options:
    	id-generator config file (default "./etc/id.conf")
  -d int
    	data center id (default -1)
  -h	this help
  -p int
    	listen on port (default 8000)
  -r string
    	router path (default "/id/next")
  -v	show version and exit
  -w int
    	worker id (default -1)
```

### Startup
```
$ id-generator -p 12345 -d 1 -w 1
```