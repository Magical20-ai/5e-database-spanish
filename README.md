# 🇪🇸 5e-database-spanish ![](https://geps.dev/progress/20)

Contiene la base de datos en español para la API de la 5ª Edición de D&D en https://dnd5e.magical20.com/

## Progreso de Traducción

Aquí puedes ver el progreso actual de la traducción de los archivos de la base de datos.

- [x] Ability Scores
- [x] Alignments
- [X] Backgrounds
- [X] Classes
- [ ] Conditions
- [ ] Damage Types
- [ ] Equipment Categories
- [ ] Equipment
- [ ] Feats
- [ ] Features
- [ ] Languages
- [ ] Levels
- [ ] Magic Items
- [ ] Magic Schools
- [ ] Monsters
- [ ] Proficiencies
- [ ] Races
- [ ] Rule Sections
- [ ] Rules
- [ ] Skills
- [X] Spells
- [ ] Subclasses
- [ ] Subraces
- [ ] Traits
- [ ] Weapon Properties

## Cómo ejecutar

### Con Docker

Deberías poder construir localmente y luego ejecutar la imagen Docker local.

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

## Despliegue de la API

Si deseas desplegar tu propia instancia de la API utilizando esta base de datos traducida, puedes seguir los pasos proporcionados en el repositorio oficial de la API de D&D 5e: [5e-srd-api](https://github.com/5e-bits/5e-srd-api).

## Código de Conducta

El Código de Conducta se puede encontrar [aquí.](https://github.com/5e-bits/5e-database-spanish/wiki/Code-of-Conduct)

## Contribuciones

¿Te gustaría contribuir a la traducción o corrección de la base de datos? ¡Genial! Agradecemos tus propuestas de contribución a través de Pull Requests.

Para contribuir, sigue estos pasos:

1. Haz fork del repositorio.
2. Crea una nueva rama para tus cambios.
3. Realiza tus cambios y asegúrate de seguir las convenciones de nomenclatura y estructura del proyecto.
4. Envía un Pull Request con una descripción clara de los cambios propuestos.

Antes de enviar tu Pull Request, revisa nuestro Código de Conducta y asegúrate de que tus cambios sean coherentes con él. Todos los aportes son bienvenidos, ¡y juntos podemos hacer de este proyecto algo mejor para la comunidad!

## Licencia

Este proyecto está licenciado bajo los términos de la licencia MIT. El material subyacente
se libera utilizando la [Licencia de Juego Abierto Versión 1.0a](https://www.wizards.com/default.asp?x=d20/oglfaq/20040123f)
