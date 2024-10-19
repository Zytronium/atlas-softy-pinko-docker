# Docker

---
This project is all about Docker.

Docker can be used sort of like a virtual machine, but quick to set up and more
customizable. Our sandboxes on the Intranet actually use Docker. Docker is
useful for application testing on specific environments. It can also be used
when testing  if you don't to make sure it won't make changes - which sometimes
may even be damaging - to your local machine.

How to run the web server for a specific task:

- CD into a directory, i.e. task 5.
- Run the following command:
```bash
docker-compose build
```
- Run the following command:
```bash
docker-compose up
```

How to connect to the server:
Depending on which task, go to one of these URLs:
- http://localhost:5252
- http://localhost:5252/api/hello
- http://localhost:80
