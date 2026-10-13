# SendGrid desde Node.js

Ejemplo que envía un correo con un PDF adjunto.

1. Ejecutar `npm ci`.
2. Crear `.env` con `SENDGRID_API_KEY` y `EMAIL_SENDER` (remitente verificado en SendGrid).
3. Colocar el PDF en `src/test.pdf` y ajustar destinatarios, asunto y cuerpo en `src/index.js`.
4. Ejecutar `npm run dev`: envía el correo una sola vez.

`npm test` es un marcador sin pruebas. Licencia: [MIT](LICENSE).
