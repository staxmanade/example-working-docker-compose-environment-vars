
If you `docker-compose up` with this, you should see the environment var from `.env` passed and printed out...

Example output

```
> docker-compose up
Starting exampleworkingdockercomposeenvironmentvars_some_server_1
Attaching to exampleworkingdockercomposeenvironmentvars_some_server_1
some_server_1  | ENV Var Passed in: Test value from .env file!
exampleworkingdockercomposeenvironmentvars_some_server_1 exited with code 0
```
