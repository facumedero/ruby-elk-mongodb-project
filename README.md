# ruby-elk-mongodb-project
# Spotify API
 Trabajo Práctico de la asignatura Base de Datos 2, de la UNLP, realizado por Balducchi Bruno, Medero Facundo y Rodriguez Gabriel. El mismo consta de una API rest orientada al dominio de Spotify o simila, con las entidades Artista, Albúm y Canción, sus correspondientes atributos.

## Requerimientos

* Ruby  ~2.6.5
* Ruby on Rails 6
* Add more

## Instalación
### Docker

Construimos la imagen con el comando:
```
  docker-compose build
```

Instalamos las gemas dependientes del proyecto con:

```
  docker-compose run web bundle install
```

Creamos y migramos la base:

```
  docker-compose run web rails db:build
```

Iniciamos el contenedor:

```
  docker-compose up
```

### Instalación Manual

Instalar las gemas:

```
  bundle install
```

Crear y migrar la base:

```
  bin/rake db:build
```
