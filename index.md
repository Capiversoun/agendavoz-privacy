# Política de Privacidad – AgendaVoz

**Última actualización:** 23 de noviembre de 2026  
**Desarrollador / Titular:** Julio Estevez (Capiversoun)  
**Contacto:** capiversoun.dev@gmail.com

Esta Política de Privacidad describe cómo **AgendaVoz** (paquete `com.capiversoun.agendavoz`) gestiona la información y los permisos del dispositivo cuando utilizas nuestra aplicación móvil.

---

### 1. Principio de Privacidad y Almacenamiento Local
**AgendaVoz** está diseñada para funcionar de manera privada en tu dispositivo:
* **Sin servidores propios:** No operamos servidores externos ni bases de datos en la nube para almacenar tus notas, tareas, eventos o grabaciones.
* **Almacenamiento 100 % local:** Toda la agenda, los recordatorios y los pendientes que creas se guardan exclusivamente en la memoria interna de tu teléfono mediante una base de datos local encriptada por el sistema operativo. Si desinstalas la aplicación o borras sus datos, toda tu información se elimina permanentemente.

---

### 2. Uso de Permisos del Dispositivo
Para cumplir con su función principal de asistente de voz y calendario, la aplicación solicita únicamente los siguientes permisos estrictamente necesarios:

* **Micrófono (`android.permission.RECORD_AUDIO`):** Se utiliza exclusivamente cuando presionas el botón de dictado por voz para convertir tus palabras en texto y crear eventos o tareas. El audio se procesa en tiempo real a través del motor de reconocimiento de voz nativo de Android / Google Speech Services y **no se graba, guarda ni envía** a ningún servidor del desarrollador.
* **Alarmas Exactas y Notificaciones (`USE_EXACT_ALARM`, `POST_NOTIFICATIONS`, `RECEIVE_BOOT_COMPLETED`):** Se utilizan exclusivamente para programar y mostrar alertas puntuales (recordatorios con sonido o silenciosos) en el horario establecido por ti, incluso después de reiniciar el teléfono.
* **Acceso a Red (`INTERNET`):** Utilizado únicamente por los servicios del sistema operativo cuando el motor de reconocimiento de voz requiere conectividad para transcribir el dictado.

---

### 3. Recopilación y Compartición de Datos con Terceros
* **No recopilamos datos personales:** AgendaVoz no solicita registro de usuario, nombre, correo electrónico, ubicación GPS ni acceso a tus contactos.
* **Sin venta ni cesión de datos:** No vendemos, alquilamos ni compartimos información de los usuarios con terceros ni redes publicitarias en esta versión.

---

### 4. Seguridad de la Información
La aplicación deshabilita las copias de seguridad automáticas no cifradas (`allowBackup="false"`) y restringe el acceso de aplicaciones de terceros a sus receptores internos de alarmas para proteger la integridad de tus recordatorios frente a accesos no autorizados dentro del dispositivo.

---

### 5. Privacidad de Menores
AgendaVoz no está dirigida específicamente a menores de 13 años ni recopila conscientemente información personal de niños.

---

### 6. Cambios en esta Política de Privacidad
Podemos actualizar esta Política de Privacidad ocasionalmente para reflejar mejoras técnicas o nuevas funcionalidades (como la eventual incorporación de servicios opcionales en futuras versiones). Cualquier modificación será publicada en esta misma página con su fecha de actualización correspondiente.

---

### 7. Contacto
Si tienes preguntas o consultas sobre esta Política de Privacidad o el funcionamiento de **AgendaVoz**, puedes escribirnos a:  
**capiversoun.dev@gmail.com**
# Privacy Policy – AgendaVoz

**Last updated:** November 23, 2026  
**Developer / Owner:** Julio Estevez (Capiversoun)  
**Contact:** capiversoun.dev@gmail.com

This Privacy Policy describes how **AgendaVoz** (package `com.capiversoun.agendavoz`) handles device permissions and user information when you use our mobile application.

---

### 1. Privacy Principle & Local Storage
**AgendaVoz** is built to operate privately on your device:
* **No External Servers:** We do not operate proprietary servers or cloud databases to store your notes, tasks, events, or voice inputs.
* **100% Local Storage:** All calendar events, reminders, and to-do items you create are stored exclusively on your device's internal storage using a local database. Uninstalling the app or clearing its storage permanently deletes all your data.

---

### 2. Device Permissions Usage
To deliver its core functionality as a voice-driven calendar and reminder manager, the application requests only the strictly necessary permissions:

* **Microphone (`android.permission.RECORD_AUDIO`):** Used exclusively when you tap the voice input button to transcribe speech into text for creating events or tasks. Audio is processed in real time by Android's native speech recognition engine / Google Speech Services and is **never recorded, stored, or transmitted** to any developer-owned server.
* **Exact Alarms & Notifications (`USE_EXACT_ALARM`, `POST_NOTIFICATIONS`, `RECEIVE_BOOT_COMPLETED`):** Used strictly to schedule and deliver timely alerts and reminders at the exact times you specify, including restoring scheduled alarms after a device reboot.
* **Network Access (`INTERNET`):** Used solely by system speech-to-text services when online processing is required to transcribe spoken commands.

---

### 3. Data Collection & Third-Party Sharing
* **No Personal Data Collected:** AgendaVoz does not require user accounts and does not collect your name, email address, GPS location, or contact list.
* **No Data Sharing or Sale:** We do not sell, rent, or share user data with third parties or advertising networks in this release.

---

### 4. Data Security
The application disables unencrypted automatic backups (`allowBackup="false"`) and restricts external broadcast access to internal alarm receivers to safeguard your schedule against unauthorized access on the device.

---

### 5. Children's Privacy
AgendaVoz is not directed at children under the age of 13 and does not knowingly collect personal information from children.

---

### 6. Changes to This Privacy Policy
We may update this Privacy Policy from time to time to reflect technical updates or future features. Any changes will be posted on this page with an updated revision date.

---

### 7. Contact Us
If you have any questions about this Privacy Policy or **AgendaVoz**, please contact us at:  
**capiversoun.dev@gmail.com**
