# Alexa developer


![utxj](https://github.com/loreasc2003/m4delProyecto/assets/163441777/57f5e0f6-567a-4597-beff-f8adc0768c60)

<br>
<br>
<h1 align="center"> Universidad Tecnológica de Xicotepec de Juárez </h1>
<br>

<h2 align="center"> Desarrollo Móvil Integral </h2>
<h2 align="center"> Alexa Developer 200187 </h2>
<h2 align="center"> Por: Hugo Sanchez Gonzalez </h2>
<br>
<h2> Objetivo </h2>
Realizar una aplicación en Flutter para Dispositivos Móviles, parte de la Unidad 2 de la asignatura de Desarrollo Móvil Integral, para comprender el usos de Stateless y Statefull Widgets.
<br>
<h2 align="center"> Documentación del proyecto </h2>



|No. |Nombre |Potenciador |Estatus |
|--|--|--|--|
|26|Amazon developer|10|⭐Activa|


<br>


<h3> Practica 21 </h3>
|
    
| Captura | Descripción | 
|:-------------:|:---------------|
| ![crearcuenta](https://github.com/user-attachments/assets/cfde9cde-fab3-47ec-b9f4-85cec86be706)  width="300" height="100" style="margin-bottom: 5px;"> | Creacion de nuestra de la cuenta de amazaon developer e iniciar sesion |

| ![alexa](https://github.com/user-attachments/assets/265854f4-7cc3-43f6-b502-836668bf8d54)  width="300" height="100" style="margin-bottom: 5px;"> |Una vez iniciado sesion damos click en developer console y escogemos alexa|

|  ![skillr](https://github.com/user-attachments/assets/cee35217-4c70-4c03-8960-eefe034b797d)  width="300" height="100" style="margin-bottom: 5px;"> | Una vez entrado en alexa le damos en el boton de create skill pones el nombre de tu skill por ejemplo clima fernando y seleccionas el idioma español y damos next|

| ![finalizadaskill](https://github.com/user-attachments/assets/a1f2cdf2-9a88-4aa4-9f0b-e6b51f7f4ce5)  width="300" height="100" style="margin-bottom: 5px;"> | ya despues en la seccion 2 seleccionar smart home y custom damos next, en la seccion 3 damos next y ya en la 4 creamos nuestra skill|
| ![invocacion](https://github.com/user-attachments/assets/bc2a290f-3c35-4335-ac54-b8360ca1d668)  width="300" height="100" style="margin-bottom: 5px;"> | nos vamos a la parte de invocacion(invocations) en skill Invocation Name cambias el nombre yo por ejemplo puse otra vez clima fernando y le damos en build skill aparacera una ventana le damos build|
|![Intents](https://github.com/user-attachments/assets/67614cb0-5d05-4b63-aa5d-dc11836b2f36)  width="300" height="100" style="margin-bottom: 5px;"> | Nos vamos Interaction Model en Intents y editamos hello world|

|![eliminar](https://github.com/user-attachments/assets/2700bb88-93af-445a-8305-75d5369f594a)  width="300" height="100" style="margin-bottom: 5px;"> | Eliminamos todo lo de hola, como estas , di hola mundo, di hola , hola mundo |
|![poner](https://github.com/user-attachments/assets/1b7eb673-e6b5-4d5e-a3c9-d40d6812f2a4)  width="300" height="100" style="margin-bottom: 5px;"> | ponemos lo que representa en la imagen y le damos en save |
|![convertir](https://github.com/user-attachments/assets/ade7d0a3-0df6-4fae-b804-2fb01a5ed3dd)  width="300" height="100" style="margin-bottom: 5px;"> | cnos dirigimos a code y le damos a convertir y ponemos lo seleccionado en la imagen |




<h3> Practica 22 </h3>

| Captura | Descripción | 
|:-------------:|:---------------|
| ![ChatView](https://github.com/user-attachments/assets/e4a7b5c5-f0fd-4d69-b5cd-356459f70c13)  width="300" height="100" style="margin-bottom: 5px;"> |El widget `_ChatView` es la vista del chat en la aplicación. Muestra una lista de mensajes en un `ListView.builder` que se desplaza y actualiza en función del estado gestionado por `ChatProvider`. Los mensajes se presentan con burbujas diferentes según quién los envíe (el usuario o la otra persona). Al final de la pantalla, hay una caja de texto donde el usuario puede escribir y enviar nuevos mensajes.|
|![mymessage](https://github.com/user-attachments/assets/976e6deb-a679-41d1-8e83-db979bdb8758)  width="300" height="100" style="margin-bottom: 5px;"> |`MyMessageBubble` es un widget que muestra el mensaje enviado por el usuario en una burbuja estilizada. El fondo de la burbuja tiene el color primario del tema, y el texto se presenta en blanco. Este widget se utiliza para la visualización de los mensajes del usuario en la interfaz de chat.|
|![othermessage](https://github.com/user-attachments/assets/6e78b227-80e2-4dae-85ca-94fbd8a50ed3)  width="300" height="100" style="margin-bottom: 5px;"> |`OtherMessageBubble` es un widget que muestra los mensajes que provienen de otra persona en la conversación. Utiliza un Container con fondo de color secundario y texto dentro de un Padding para estilizar los mensajes. |
|![imagen](https://github.com/user-attachments/assets/3a526908-513a-4da1-9250-9768750221a2)"  width="300" height="100" style="margin-bottom: 5px;"> |`_ImageBubble` es un widget diseñado para mostrar una imagen dentro de una burbuja de mensaje. Maneja el proceso de carga de la imagen y muestra un mensaje indicativo de que la imagen se está descargando. Además, la imagen tiene bordes redondeados y se ajusta al tamaño de la pantalla de forma responsiva, asegurando que se vea correctamente en diferentes dispositivos.| <img src="https://github.com/user-attachments/assets/084827b5-ff25-4de8-bb53-90f028e772fa"  width="300" height="100" style="margin-bottom: 5px;"> |El widget `MessageFieldBox` crea un campo de texto estilizado con un borde redondeado y un botón de envío. Permite al usuario escribir mensajes, y al presionar el icono de envío o la tecla Enter, se llama a una función onValue con el texto ingresado. Además, incluye un manejo del foco y de la interacción con el teclado.|

<h3> Practica 23 </h3>

| Captura | Descripción | 
|:-------------:|:---------------|
| ![yesnomodel](https://github.com/user-attachments/assets/2cc88793-1164-4931-8d68-4940fae6c6ac)
  width="300" height="100" style="margin-bottom: 5px;"> |El código define la clase `YesNoModel`, que se utiliza como modelo de datos para manejar respuestas del tipo "sí o no" provenientes de una fuente externa . Incluye métodos para convertir instancias desde y hacia formatos JSON, y para transformarlas en una entidad del dominio llamada `Message`.|
| ![chatprovider](https://github.com/user-attachments/assets/e3faa639-3fc6-4ea1-b783-39ac28cc211d)  width="300" height="100" style="margin-bottom: 5px;"> |La clase `ChatProvider` es el núcleo del manejo del estado del chat. Coordina las acciones entre el envío de mensajes, la recepción de respuestas automáticas, y la actualización visual de la interfaz.|
|![getyesnoanswer](https://github.com/user-attachments/assets/89e2af51-8984-4009-9c8a-79ed3e16e9e4)  width="300" height="100" style="margin-bottom: 5px;"> |La clase `GetYesNoAnswer` actúa como un puente entre la API de yesno.wtf y la lógica de la aplicación. Realiza solicitudes HTTP, transforma las respuestas en objetos internos, y permite integrar respuestas automáticas en el flujo del chat, completando la experiencia interactiva de la aplicación.| <img src="https://github.com/user-attachments/assets/226e7ef8-7894-4dc0-88bc-f10f6539490c"  width="300" height="100" style="margin-bottom: 5px;"> |El método `moveScrollToBottom` mejora la experiencia de usuario al garantizar que los mensajes más recientes sean visibles sin requerir interacción manual, proporcionando un desplazamiento suave hacia la parte inferior de la lista.|

## Resultados

![resultado](https://github.com/user-attachments/assets/9abf27e0-978b-47a6-8827-3ea22d9befe9)
















