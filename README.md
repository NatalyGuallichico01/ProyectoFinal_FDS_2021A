# SportFiel
El siguiente proyecto muestra el desarrollo de un Sistema Web, que permite a los usuarios agendar un turno para alquilar canchas deportivas o a su vez para la inscripción en algun curso ofertado por la misma.
Video demostrativo: [Link](https://youtu.be/XHwnhfMY__c "Link")

**Realizado por:**

Luis Catota

Nataly Guallichico


###  1. Herramientas de Desarrollo
##### FIREBASE
Esta plataforma se ha empleado por su base de datos NoSQL con capacidad de sincronización en tiempo real y asistencia sin conexión de los datos que se almacenan, así mismo otra razón es su servicio de hosting que permite alojar el Sistema Web.
##### REACT
Es una biblioteca de JS que permite crear interfaces de usuario de formar sencilla y con un alto nivel de interacción, se basa en componentes   los cuales se actualizan y se renderizan al cambiar los datos. 
###2. Estructura y Arquitectura
#####Arquitectura
La Arquitectura del Sistema Web se muestra en la siguiente imagen. 

![arquitectura_SportField](https://user-images.githubusercontent.com/74806895/133349146-c6564944-6e57-4fcd-acdd-a5ffd01010cb.png)
Los datos almacenados en Firebase muestran la siguiente estructura
![arquitectura_BDD_SF](https://user-images.githubusercontent.com/74806895/133349551-6db37212-594d-4c4e-ac37-d7594c0380a2.png)

###3. Funcionalidades principales

Dentro del desarrollo del Sistema Web se pudo considerar varios requerimientos y funcionalidades para el Sistema Wed, algunas de las más relevancia son las siguientes:

##### - Registro e inicio de sesión para los usuarios

El usuario podrá iniciar sesión luego de registrarse dentro del Sistema Web, utilizando un nombre de usuario y una contraseña generado por el mismo al momento de llenar el formulario de registro, para esto fue necesario activar un método de autenticación generado en Firebase Authntication habilitando User/Password.

![login](https://user-images.githubusercontent.com/74806895/133351378-196b68d9-7c2b-4612-92bb-38824f9893ba.PNG)

##### - Visualizacion de la ventana principal (HomePage)

El usuario podrá ver todo lo que ofrece esta aplicación, tales como el agendamiento de canchas deportivas e inscripción en cursos ofertados.

![HomePage_Carusel](https://user-images.githubusercontent.com/74806895/133351812-77083a90-9e6f-4fbf-b800-8010b3d500a6.PNG)
![HomePage_Servicios](https://user-images.githubusercontent.com/74806895/133351910-734d4409-0fa5-4d22-8053-a335f4a7dc86.PNG)
![HomePage_Cursos](https://user-images.githubusercontent.com/74806895/133352026-5839b75e-a237-449c-8ec7-0a692ccf2240.PNG)

##### - Perfil de usuario

Los usuarios podrán visualizar su perfil donde podrán agendar una cancha, inscribirse en un curso y dejar un comentario.

![perfilUser](https://user-images.githubusercontent.com/74806895/133360787-18bdec87-479c-4b88-a9eb-2da23ca45e88.PNG)

##### - Pasos para agendar una cancha

Los usuarios tendran instrucciones acerca de como agendar una canchar.

![canchas](https://user-images.githubusercontent.com/74806895/133361245-f6c4b62c-ce00-4938-8dc6-37a373739392.PNG)

### 4. Versiones de Desarrollo

![desarrollo](https://user-images.githubusercontent.com/74806895/133362824-ef66836a-4324-4dbe-8cba-1be88c8cc904.PNG)

### 5. Instalación 
##### 5.1 Clonar el Repositorio
git clone https://github.com/NatalyGuallichico01/ProyectoFinal_FDS_2021A.git
##### 5.2 Instalar dependencias
npm install
##### 5.3 Levantar firebase
npm install firebase
###  6. Anexos
En el siguiente link se encuentra toda la documentacion tales como: Manual de Instalación, Informe Técnico, Manual Técnico. [Link](https://drive.google.com/drive/folders/1CGxTz6rc2mdMSiOXoc4HLf1br5GDFLEP?usp=sharing "Link")
