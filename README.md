<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest


# Teslo Shop API

1. Clonar proyecto

2. Instalar todas las dependencias del proyecto
```
yarn install
```
3. Clonar el archivo __.env.template__ y renombarlo a __.env__

4. Asignar sus propias variables de entorno


5. Levantar la base de datos
```
docker-compose up -d 
```

6. Para forzar eliminacion de carpeta postgres  __solo si es necesario__
```
chown <username> postgres
```

7. Levantar la aplicacion en modo desarrollo
```
yarn start:dev
```
