todobackend-http4s
==================

An [http4s](http://http4s.org/) implementation of the [Todo-Backend](http://www.todobackend.com/) project

## Example API calls using [HTTPie]

```bash
http --json POST :8080/todos title=Hello
http :8080/todos
http :8080/todos/0
http --json PATCH :8080/todos/0 title="Hello world"
```

[HTTPie]: https://httpie.org/
