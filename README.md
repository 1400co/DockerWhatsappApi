<p align="center">
  <a href="https://builderbot.vercel.app/">
    <picture>
      <img src="https://builderbot.vercel.app/assets/thumbnail-vector.png" height="80">
    </picture>
    <h2 align="center">WhatsApp API Project</h2>
  </a>
</p>

<p align="center">
  Este proyecto ha sido creado por Oscar Rueda utilizando BuilderBot.
</p>

## Acerca del Proyecto

Este proyecto implementa una API para WhatsApp, permitiendo la construcción de flujos de conversación automatizados, respuestas automáticas a preguntas frecuentes, recepción y respuesta automática a mensajes, y seguimiento de interacciones con los clientes. Utiliza `@builderbot/bot` para crear los flujos de conversación y `@builderbot/provider-baileys` como proveedor de WhatsApp.

### Características Principales

- Flujos de conversación automatizados agnósticos al proveedor de WhatsApp.
- Configuración de respuestas automáticas para preguntas frecuentes.
- Recepción y respuesta automática a mensajes.
- Seguimiento de interacciones con clientes.

## Iniciando

Para comenzar con este proyecto, primero clona el repositorio y luego sigue los comandos de Docker para construir y lanzar la aplicación.

```
pnpm i
```

### Comandos de Docker

Para construir la imagen de Docker de la aplicación y lanzarla en el puerto 3008, ejecuta los siguientes comandos:

```bash
docker build --build-arg PORT=3008 -t whatsapp-api:latest .
docker run -d -p 3008:3008 whatsapp-api:latest


## Documentation

Visita [builderbot](https://builderbot.vercel.app/) para ver la documentacion.


## Official Course

Si quieres aprender mas puedes ingresar al curso
[View Course](https://app.codigoencasa.com/courses/builderbot?refCode=LEIFER)


