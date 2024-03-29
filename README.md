# 5e-database-spanish (EN PROGRESO)

Contiene la base de datos en español para la API de la 5ª Edición de D&D en http://dnd5eapi.co/

## Cómo ejecutar

### Con Docker

Deberías poder construir localmente y luego ejecutar la imagen Docker local. Esto se puede hacer de una de dos maneras:

1. Si solo necesitas una imagen y no estás ejecutando en un M1:

```bash
docker run ghcr.io/5e-bits/5e-database:latest
```

2. Si estás ejecutando en un M1 o quieres probar cambios que has realizado en la Base de Datos:

```bash
docker build -t 5e-database .
docker run -i -t 5e-database:latest
```

### Sin Docker

Primero necesitas asegurarte de tener [MongoDB instalado localmente.](https://docs.mongodb.com/manual/installation/)

Puedes cargar estos datos localmente ejecutando:

```bash
MONGODB_URI=mongodb://localhost/5e-database npm run db:refresh
```

## Código de Conducta

El Código de Conducta se puede encontrar [aquí.](https://github.com/5e-bits/5e-database/wiki/Code-of-Conduct)

## Licencia

Este proyecto está licenciado bajo los términos de la licencia MIT. El material subyacente
se libera utilizando la [Licencia de Juego Abierto Versión 1.0a](https://www.wizards.com/default.asp?x=d20/oglfaq/20040123f)
