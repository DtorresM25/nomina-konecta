# nomina-konecta

## Crear imagen de docker

```bash
# Construir imagen de docker
docker build -t nomina:tag_name .

```

## desplegar como contendor de docker

```bash
# desplegar contenedor con la aplicacion
docker run -d -p 8080:8080 nomina:tag_name

```

## Documentacion de endpoint (swagger)

```bash
# acceda a la documentacion generada por swagger del end-point para calcular la fecha de pago de la nomina (puede probar la funcionalidad directamente desde aqui)
http://localhost:8080/swagger-ui/index.html

```
