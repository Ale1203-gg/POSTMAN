# POSTMAN
##  ¿Qué es Postman?  
Postman es una herramienta utilizada para **desarrollar, probar y documentar APIs**.  
Facilita la interacción con **APIs REST y SOAP**, permitiendo enviar **solicitudes HTTP** (GET, POST, PUT, DELETE) y ver sus respuestas de forma clara.  

 **Usos principales:**  
- Pruebas de API sin necesidad de programar.  
- Automatización de pruebas.  
- Documentación de endpoints.  
- Simulación de peticiones desde un cliente.  

---

##  Relación con los Temas Anteriores  

###  **1. Linux y SSH**  
En nuestros proyectos, **Linux y SSH** nos permiten acceder y administrar servidores remotos, como los de **Oracle Cloud** o una **VPS**.  
Postman complementa esto al permitirnos probar APIs que corren en estos servidores sin necesidad de un navegador.  

###  **2. HestiaCP y Hosting**  
HestiaCP nos ayuda a gestionar servidores y dominios, mientras que **Postman** nos permite probar APIs alojadas en estos servidores, asegurando que la comunicación entre el backend y el frontend funcione correctamente.  

###  **3. Creación de un Dominio y DNS**  
Postman puede ser útil para probar conexiones HTTP con nuestro **dominio** después de configurarlo en **Hostinguer o Oracle Cloud**.  
Podemos enviar solicitudes a `https://midominio.com/api` y verificar que la configuración esté correcta.  

###  **4. Apache, PHP y Desarrollo Web**  
Si estamos creando una página web con **Apache y PHP**, **Postman** nos permite probar los endpoints de nuestra API antes de integrarlos en el frontend.  
Ejemplo de prueba en Postman para una API en PHP:  

```http
POST https://midominio.com/api/login.php  
Body (JSON):
{
  "usuario": "admin",
  "password": "1234"
}
