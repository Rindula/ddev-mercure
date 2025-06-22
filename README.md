[![tests](https://github.com/Rindula/ddev-mercure/actions/workflows/tests.yml/badge.svg)](https://github.com/Rindula/ddev-mercure/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2025.svg)

# Mercure extension for ddev

This extension is based on [dunglas/mercure](https://github.com/dunglas/mercure)s implementation.

To install it, for DDEV v1.23.5 or above run

```sh
ddev add-on get Rindula/ddev-mercure
```

For earlier versions of DDEV run

```sh
ddev get Rindula/ddev-mercure
```

The mercurehost will be available under `mercure.${DDEV_HOSTNAME}`.
So for `example.ddev.site` the url will be `mercure.example.ddev.site`.
From inside the web container, you can reach mercure under `http://mercure:3000`.
