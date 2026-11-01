# Voz: objetivo y dependencias

La personalidad puede aplicarse antes que la voz. Este repositorio no configura ElevenLabs automáticamente.

Objetivo sonoro: conservar una voz autorizada por el propietario, con interpretación estable y reverberación local original de mezcla 0.3. Referencia de calibración aceptada en Hermes: estabilidad 0.5, similitud 0.75, estilo 0 y refuerzo del hablante activado, modelo eleven_multilingual_v2. Estos controles no garantizan una emoción; la redacción también importa.

## Antes de integrar en Muse

Comprobar qué herramientas, conectores o servicios de audio puede utilizar la cuenta. Distinguir:

- Voz nativa del cliente Muse: no está verificado que pueda sustituirse por una voz de ElevenLabs.
- Audio generado mediante un servicio externo y entregado como archivo: requiere una integración compatible y no equivale a cambiar la voz nativa.
- Voz exacta de Hermes: además de ElevenLabs necesita su IR original y procesador local. Los activos, identificadores de cuenta y credenciales se conservan en el repositorio privado del propietario; no están en este paquete.

Si hay una vía compatible, el propietario deberá configurar credenciales por un mecanismo privado. No solicitarlas en este repositorio, issues, archivos públicos o mensajes de instalación. No cambiar la voz ni ejecutar gastos por el solo hecho de leer esta guía.

## Criterios para declarar voz predeterminada

1. Integración y permisos disponibles y autorizados.
2. Voz y activos originales recuperados desde una fuente privada autorizada, con integridad verificada.
3. Una sola ruta de generación configurada; no depender de que el modelo improvise scripts.
4. Registro de voz, parámetros, preset y archivo concreto generado, sin credenciales.
5. Prueba real en una conversación nueva de web y móvil, con escucha del propietario.
6. Persistencia y procedimiento de recuperación comprobados.

Mientras falte alguno, informar el estado como pendiente. Los efectos de avería recreativa no son la voz habitual y se aplican solo cuando se pidan explícitamente. No están implementados por este paquete.
