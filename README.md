# lealone-rpc

lealone-rpc js client, A rpc client for lealone, more detail go to https://github.com/lealone/Lealone


## Usage

rpc by HTTP

```
// set server host path
lealone.setServiceUrl('http://localhost:8080/service');

// get rpc service
const userService = lealone.getService('teacher_server');

// rpc execution
userService.addUser('xiaoming', 12, (id: number) => {
  console.log(id, 'success')
});
```


## TODO

- typescript
- sock rpc