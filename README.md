# INTRODUCCIÓN A AZURE
## SESIÓN 2 PRÁCTICA 1
En este apartado aprenderas a realizar una creación de Wordpress en App Service

**Requisitos**
Para el desarrollo de esta práctica necesitamos tener:
* Iniciar sesión en el portal de azure
* Créditos disponibles Azure. 

En caso de ser estudiante se puede recurrir al uso del correo institucional para obtener una git student developer pack.

--------------------------------------------------------------
Una vez que ya hayamos iniciado sesión esta será la primera página que visualizaremos
![](/images\portalAzure.png)

En esta primera página seleccionamos el servicio que dice "Marketplace"
![](/images\marketplace.png)
 
Dentro de Marketplace, nos dirigimos al buscador y buscamos "Wordpress", seleccionamos la primera opción.
![](/images\marketplace2.png)

Nos dirigira a la siguienta ventana y damos clic en crear.
![](/images\crear.png)

-----------------------------------------------
Se nos mostrará la siguiente ventana, donde tenemos que llenar los siguientes rubros:
* Grupo de recursos: en caso de no contar con un grupo de recursos creamos uno nuevo.
* Región: aqui seleccionamos la opción donde querramos que se aloje nuestro servidor. Es recomendable que sea en la región más cercana posible
* Nombre: elegimos el nombre que deseamos tenga la aplicación web.
*Sistema Operativo: seleccinamos que el SO sea Windows.
![](/images\creacion.png)

Ahora bien, nos dirigimos al apartado "Etiquetas", para esta página esta bien con que solo agreguemos una etiqueta. 
PD. Las etiquetas nos ayudan a visualizar un mejor manejo de los recursos.
![](/images\etiquetas.png)

Una vez agregada nuestra etiquta nos vamos a "Revisar y Crear". Aqui visualizaremos un resumen de todos los datos que completamos anteriormente.
![](/images\revisar.png)
![](/images\revisar2.png)
![](/images\revisar3.png)

Visualizado nuestro resumen damos clic en "CREAR". 
Cargara una nueva pestaña, donde nos ira mostrando la implementacion del recurso que acabamos de crear.
![](/images\implementacion.png)

¡Una vez finalizada la implementación nos mostrara nuestro nuevo recurso!

Seleccionamos "Ir al recurso"
![](/images\recurso1.png)

Tenemos una ventana que nos muestra todos los datos sobre nuestro nuevo recurso. 
Nos dirigimos al apartado de "Información esencial" para dar clic a nuestra nueva url y continuar con una configuración básica.
** http://prubea.azurewebsites.net/wp-admin/install.php **

![](/images\url.png)

 --------------------------------------------
Se abrira una nueva pestaña, donde el primer paso será elegir el idioma con el que deseamos continuar la configuración. Una vez elegido damos clic en el botón "Continuar"
![](/images\idioma.png)

Se abrira el proceso de instalación de WordPress que no nos tomará más de cinco minutos. Simplemente completamos la información siguiente y estaremos listos para usar la más enriquecedora y potente plataforma de publicación personal del mundo. 
Al finalizar el llenado de datos damos clic en "Instalar Wordpress"
![](/images\datos.png)
![](/images\datos2.png)

Para visualizar el inicio de nuestra página, borramos el texto que esta comienza apartir de wp:
![](/images\borrar.png)
![](/images\borrar2.png)

 **Listo nuestra aplicación con wordpress a finalizado** 
 ![](/images\final.png)

-----------------------------
**Importante**
Una vez finalizada la práctica te recomendamos detener todos los servicios que integran los recursos de esta práctica, ya que, si suentas con una cuenta de estudiante tus créditos se acabaran mientras estos recursos sigan corriendo, se pueden detener o eliminar completamente.
![](/images\eliminar.png)


