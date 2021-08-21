## Django on Docker Boilerplate

This is a boilerplate for running django application on docker containers. The boiler plate includes gunicorn as the WSGI, postgresql as the backend and nginx to serve http/https requests as well as static files.

<br>
<br>

### Requirements

- python
- pip
- docker

<br>

### Getting Started

- Add your django project to the /app/ directory
- Add your dependencies to the requirements.txt or run this to generate it:
  ```
  pip freeze > requirements.txt
  ```
- Modify the .env, .env.db and settings.py files according to your environment

<br>

### Usage

```
docker-compose up -d
```
