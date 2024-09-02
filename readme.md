
1. Revisar el volumen montado en `docker-compose.yml` para que coincida con la carpeta donde está la web de Jekyll.
2. Revisar que el tag sea la última versión del repositorio de `pages-gem`. Actualmente v232: [https://github.com/github/pages-gem.git#v232](https://github.com/github/pages-gem.git#v232)

```
docker compose up
```

[http://0.0.0.0:4000/](http://0.0.0.0:4000/)

en Windows por alguna razón abrirlo en [http://localhost:4000/](http://localhost:4000/) aunque esté asociada la 0.0.0.0
