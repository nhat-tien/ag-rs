

```
server Applicaton {
	port = 6767,
	routes = [
	  [ "/", "get", () { "Hello world" } ]
	]
}
```