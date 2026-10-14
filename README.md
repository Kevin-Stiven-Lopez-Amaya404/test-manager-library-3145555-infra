# Infraestructura

PostgreSQL inicia vacío y el esquema pertenece a las migraciones versionadas de `api`.

## Arranque local

Con Docker Desktop iniciado:

```bash
docker compose up --build
```

- Frontend: http://localhost:5173
- API: http://localhost:8000/health
- Usuario inicial: `admin` / `change-me`

Para datos de demostración, ejecuta `python seed.py` desde `tool` apuntando a `http://localhost:8000/api/v1`.
