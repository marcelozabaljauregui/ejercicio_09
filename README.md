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

Node ports y Base de datos

![Base_de_Datos](https://user-images.githubusercontent.com/18450145/138619421-5666c92c-55e1-4cf9-b2c7-1830f51c67b0.PNG)

Aplicación

![Aplicacion](https://user-images.githubusercontent.com/18450145/138619431-1efa43e3-1712-47f2-814c-e499e61c6b74.PNG)

___
_NOTA_: Ahora que lo subí me doy cuenta que podría armar otro .yaml con el usuario y contraseña del postgres
___
