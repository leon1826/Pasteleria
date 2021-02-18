# Pasteleria


## Integrantes 

Lindsey katherine Camargo Beltran - 20172020037

Brayan Esteban Leon Pinto - 20141001002

## Proposito del sistema

Se desarrollará un aplicativo que permita por medio de una interfaz gráfica realizar la compra descrptiva de unos pasteles, y estos se mostraran al pastelero para que este pueda realizar el mismo para la fecha solicitada por el cliente y con las respectivas especificaciones.

## Roles
Usuario-Cliente: persona  que interactua en la aplicacion para generar un pedido de torta con caracteristicas especificas
Usuario-Administrador: Pastelero o administrador que gestiona el estado de los pedidos asi como la consulta de los mismos

## Requerimientos

Como cliente puedo escoger una torta y seleccionar tipo masa, relleno, cubierta y fecha de entrega

Como cliente puedo ver imagenes para escoger el tipo de decoracion de mi torta

Como cliente puedo enviar observaciones para especificar aun mas la decoracion

Como cliente puedo llenar sus datos para la facturacion del pedido

Como cliente puedo realizar el pago para formalizar y finalizar mi pedido

Como cliente necesito saber el costo de mi pedido (antes de pagarlo) para aprobar o no mi pedido

Como pastelero puedo ver una lista de los nuevos pedidos en orden de entrega

Como pastelero puedo marcar un pedido como entregado para descartarlo de la lista

Como cliente necesito ver mi factura de compra para asegurar que el pago fue correcto

## Historias de usuario
  

    |   | Historias de usuario |   |  
-- | -- | -- | -- | --
ID. de la historia | Rol | Característica / Funcionalidad | Razón /Resultado | Criterio de aceptación | Complejidad
1 | Usuario   cliente | Registrarme   en la pagina | Poder   realizar un pedido | Datos   completos | Baja
2 | Usuario-cliente-administrador | Login | Ingresar a la pagina | Datos registrados previamente | Baja
3 | Usuario-cliente- administrador | Logout | Salir de la pagina   satisfactoriamente | Haber hecho login previo | Baja
4 | Usuario-Cliente | Actualizar datos | Tener datos actuales del usaurio | Correo electrónico validado | Baja
5 | Usuario-Cleinte | Generar pedido | Crear un pedido de torta con características   especificas | Todas las características y   fecha deben estar completas, asi mismo que se haga efectivo el pago | Alta
6 | Usuario-cliente | Pagar pedido-torta | Pagar la torta para confirmar el pedido y que   este sea registrado en la base de datos | Fecha previa aceptable, pasarela de pago | Alta
7 | Usuario cliente | Consultar pedido | Obtener información del pedido   previamente realizado , como fecha y hora de entrega | Usuario con pedido previamente   registrado | Media
8 | Usuario cliente | Modificar pedido | Modificar fecha, hora y características del pedido | Antelación de 3 dias hábiles para la entrega | Alta
9 | Usuario cliente | Cancelar pedido | Cancelar el pedido | Antelación de 4 dias hábiles para   fecha pactada de entrega, segenenra sobrecargo | Alta
10 | Usuario-clieente | Consultar historial | Obetener información de pedidos anteriores   relacionados con el cliente | Usuario previamente registrado y con relación a   pedidos | Media
11 | Usuario-administrador | Consultar pedidos | Deseo obtener información del   pedido mas cercano asi como la lista de pedidos siguientes | Pedidos organizados por fecha   de entrega | Alta
12 | Usuario-Admnistrador | Cambiar estado | Deseo cambiar el estado de un pedido como entregado   , en proceso, etc | Pedidos deben estar previamente registrados, para   la correcta actualización | Alta
13 | Usuario -Administrador | Consultar historial | Deseo obtener el historial de   todos los pedidos filtrado por fecha | Pedidos que hayan sido   entregado satisfactoriamente | Media


## Prototipos de pantalla 

## Tiempo estimado 
![Tabla](https://user-images.githubusercontent.com/54810276/95878667-187cdd80-0d3b-11eb-8fa2-524b0d21198b.PNG)
Componente | Tipo de Componente | Nivel de   complejidad | Puntos de función
-- | -- | -- | --
Login | Entrada externa | Bajo | 3
Actualización usuario | Entrada   externa | Bajo | 3
Registrar pedido | Archivo lógico interno | Alta | 10
Consultar pedido | Consulta externa | Medio | 6
Consultar historial   de pedidos | Salida externa | Alta | 15
Generar pedido | Archivo   externo interfaz-lógico interno | Alta | 10
Modificar pedido | Entrada externa | Alta | 6
Consultar pedidos pendientes | Salida   externa | Alta | 15
Mostrar pedidos   pendientes | Archivo externo   interfaz | Alta | 10
Pago pedido | Salida   externa | Alta | 15
Confirmación pedido | Salida externa | Media | 10

- A partir de la tabla, el punto de funcion no ajustado es de 103
- Con el ajuste del 5% se aproxima a 108.15
- Suponiendo que el equipo toma por punto de funcion 5 horas 
- El proyecto tomaria 515 horas
- Teniendo en cuenta que son 6 horas productivas el proyecto tomaria 86 dias para ser realizado
- Si tomamos en cuenta que se trabajan 5 dias por semana, al equipo le tomaria 17,5 semanas por lo tanto poco mas de 4 meses

## Diagramas de casos de usos

![image](https://user-images.githubusercontent.com/54810276/108358560-dc5ffa80-71bc-11eb-8161-5fc778b1b35e.png)
![image](https://user-images.githubusercontent.com/54810276/108358578-e3870880-71bc-11eb-8d6a-d786fcdd2842.png)
## Diagramas de actividades 


## Diagramas de secuencia 

![Realizar la compra](https://user-images.githubusercontent.com/54810355/108276641-2063e880-7146-11eb-9c4a-5d7a92890739.jpg)
