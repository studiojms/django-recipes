# django-recipes

A initial Django API project about recipes

## Setup

To run some command, execute it from the container like

```sh
docker compose run --rm app sh -c "command"
```

### Running tests inside dev-container

```sh
cd app
python manage.py test
```

### Creating migrations

```sh
python manage.py makemigrations
```