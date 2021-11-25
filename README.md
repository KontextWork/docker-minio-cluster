# WAT

Host your own minio object storage including Traefik for TLS offloading.

# Usage

```bash
$ cp .env.example .env
```

Adjust the values in the `.env` to your use case.

Then run:

```bash
$ docker-compose up -d
```

# Access

By default you can access the gui using `gui.<MINIO_DOMAIN>` - using the user/password you provided in your `.env` file
