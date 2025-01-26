# ia-whatsapp
Tecnologías Utilizadas en el Proyecto
Node.js:

Framework de JavaScript del lado del servidor utilizado para construir el backend.
Permite crear aplicaciones ligeras y eficientes gracias a su modelo asíncrono basado en eventos.
Express.js:

Un framework minimalista para Node.js que facilita la creación de servidores web y APIs REST.
Es utilizado para manejar las rutas y solicitudes HTTP de WhatsApp y otras integraciones.
Axios:

Librería para realizar solicitudes HTTP.
Se utiliza para interactuar con las APIs externas de Shopify, WhatsApp (Twilio) y OpenAI.
Twilio API para WhatsApp:

Plataforma utilizada para gestionar mensajes de WhatsApp.
Maneja el envío y recepción de mensajes con clientes, incluyendo respuestas automatizadas.
Shopify API:

Proporciona acceso a información sobre pedidos, inventarios y clientes.
Permite sincronizar datos en tiempo real entre el agente de IA y Shopify.
OpenAI API:

Se utiliza para procesar las consultas de los clientes con inteligencia artificial.
Responde de manera profesional y clara utilizando modelos de lenguaje avanzados como GPT.
Body-parser:

Middleware para analizar solicitudes JSON y facilitar el manejo de datos enviados desde WhatsApp.
Heroku, Vercel o AWS (opcional):

Plataformas recomendadas para el despliegue de la aplicación
