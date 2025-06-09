

A functional programming language to build robust backend service 
```
{
	port = 6767,
	routes = [
       {
          path = "/",
          method = "get",
          handle = () { 
             return "Hello world!";
          }
       }
    ]
}
```
