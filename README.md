# podman_hints
podman_hints


<h1>Delete Everything!</h1>

Use with caution

``
podman system reset
``



<h1>podman-compose</h1>

``podman-compose logs``

``podman-compose up -d``


<h1>Import env vars</h1>

```export $(cat my_app/.env_db | xargs)```

within that file

```MYVAR='somevalue'```
