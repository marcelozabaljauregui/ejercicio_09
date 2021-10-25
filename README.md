# Ejercicio 09 

## Ejecución

Ejecutar primero el deployment de la base de datos

```
kube -n arba apply -f postgres_deployment.yaml
```

Luego ejecutar el deployment del web.

```
kube -n arba apply -f web_deployment.yaml
```

## Screenshots

Node Ports



Base de datos



Aplicación



