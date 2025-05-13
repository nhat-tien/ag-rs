

A programming language that compile to backend server
```
Server {
	port = 6767,
	routes = [
       {
          path = "/",
          method = "get",
          fn = (ctx: AppContext) { 
             return "Hello world!";
          }
       }
    ]
}
```

```
let a = 5;
let b = 3 + 4;
let c = "hello";

let d = {
   foo = 234
};

let e = d.foo + 2;

if e > 3 {
  a = 32;
} else {
  b = 23;
}
```
