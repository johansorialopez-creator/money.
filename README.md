# money.
🔄 Flujo de Automatización:
1. Registro de nuevos pacientes

Se coloca un QR o link en la recepción o en redes sociales que abre un formulario (Google Forms).

El paciente completa sus datos.

Zapier automatiza:

Guarda la info en una Google Sheet / Notion.

Envía un email o WhatsApp de bienvenida con instrucciones para agendar su cita.

2. Agendamiento de cita

El paciente elige su cita mediante Calendly o Google Calendar con reservas activadas.

El sistema bloquea el horario y:

Guarda la cita en el calendario del dentista.

Notifica a recepción.

Envía confirmación automática al paciente.

3. Recordatorio automático de citas

24h y 2h antes de la cita, se envía un mensaje automático por WhatsApp o email al paciente (vía Zapier o Twilio):

Hola [Nombre], te recordamos tu cita dental mañana a las [Hora].
Si no puedes asistir, responde CANCELAR.

4. Cancelación o reprogramación automática

Si el paciente responde "CANCELAR", el sistema:

Marca la cita como cancelada.

Ofrece reprogramar con un enlace.

Libera el horario en el calendario.

5. Seguimiento post-tratamiento

2 días después de la cita, se envía un mensaje:

Esperamos que estés bien tras tu cita con el Dr. [Nombre].
¿Cómo te sientes hoy? ¿Hay algo que debamos saber?


También se puede incluir una encuesta de satisfacción (Google Forms).
