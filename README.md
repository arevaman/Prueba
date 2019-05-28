# HEAL IN ONE CLICK

### descripcion
es un sistema por el cual se pueden solicitar medicamentos con formula medica o sin formula medica la cual se entre presencial mente o en versiones posteriores a domicilio


### Prerequisitos
principalmente un servidor de no muchos recursos mientras mas recursos disponga mejor para el proceso a realizar, el servidor tendra que tener instalado nodejs y nginx para el manejo del codigo bakend y frontend de todo el sitio ademas de esto es requerido un dominio y una base de datos de tipo SQL para manejar de relacion entre los datos procesados.

### Codigo En Desarrollo

Para la realizacion o usabilidad de un codigo en desarrollo es necesario tener nodejs, base de datos SQL y instalar todas las dependencias necesarias para tener un codigo funcional y como paso siguiente iniciar el servidor con todo el codigo funcionando correctamente para esto se puede usar el siguiente codigo 

~~~~
npm i or yarn install
npm run dev o yarn dev
~~~~

### Codigo En Produccion

Para colocar el sitio en produccion es necesairo instalar pm2 para el manejo de caida de la informaicon en el cual se tendra en cuenta que si el sitio se cae por cualquier razon este se vuelva a levantar sin problema alguno

~~~~
npm install pm2 -g
pm2 start index.js
~~~~

luego te realizar la configuracion del codigo y el sitio este corriendo es necesario configurar nginx para que este apunte a el servidor y al puerto en donde se esta trabajando.


### Contributing

Para realizar contribuciones a el codigo es necesario realizar un pull request y despues de una seria revision el codigo sera agregado o tendra notas de correcciones necesarias para corregir una vez corregidas o si son aceptadas las contribuciones estas seran agregadas en la siguiente version del codigo

### License

MIT License Copyright (c) 2019 DrogStock.org
