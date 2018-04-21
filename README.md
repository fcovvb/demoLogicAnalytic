# demoLogicAnalytic
Global Azure Bootcamp

Setup:
  -Crear Forms en Office 365
    >Con la pregunta "Qué #hashtag buscarémos?"
  -Crear recurso en Azure: Text Analytic API
  -Crear recurso en Azure: SQL Database (como servicio, no server)
    >Crear Tabla en nuestra base de datos
                  CREATE TABLE tweets
            (
            Nombre   varchar(50),
            Text     text,
            Stat     text,
            Magnitud float
            );
       *Pueden conectar la base de datos como servicio a un cliente SQL
       **También es posible hacer la query en el portal de Azure
  -Crear recurso en Azure: Logic Apps
   
Construyendo el flujo de Logic Apps
  >Desencadenador a gusto (Por simplicidad --> Conector Forms: "Al ingresar un nuevo registro") //En este caso hay que conectar el Flow/logic Apps con nuestra cuenta de Office 365
  >Crear un "para cada / for each", ingresando el campo id del forms ya creado
