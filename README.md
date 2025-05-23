🛡️ Simulación de Ransomware – Examen Final de Criptografía

📚 Descripción
Este proyecto es una simulación académica de un ataque de ransomware, desarrollado como examen final del curso de Criptografía de la Universidad del Norte. La simulación implementa los componentes clave de un ransomware real, pero de forma segura y controlada en un entorno educativo.

⚠️ Advertencia: Este proyecto es únicamente con fines educativos. El uso indebido de técnicas criptográficas para crear malware real es ilegal y está penado por la ley.

🧪 Contenido del Proyecto
ransomware_simulado.ipynb: Contiene toda la lógica del ransomware simulado, incluyendo:

Generación de certificados digitales RSA (2048 bits) para atacante y víctima.

Implementación del protocolo de intercambio de claves AKE v2.

Derivación de clave simétrica mediante KDF (SHA-256).

Cifrado de archivos con AES-256-CBC.

Simulación de la notificación al usuario afectado.

Recuperación de archivos cifrados tras el pago simulado.

Verificación de integridad de los archivos con SHA-256.

⚙️ Requisitos
PyCryptodome

Google Colab (recomendado para ejecutar)

Instalación de dependencias (si lo ejecutas localmente):

bash
Copy
Edit
pip install pycryptodome
🚀 Ejecución
Abre el archivo ransomware_simulado.ipynb en Google Colab.

Ejecuta las celdas en orden para simular:

El establecimiento del secreto común con AKE v2.

El cifrado de archivos seleccionados.

La notificación de rescate.

La recuperación de archivos tras simular el pago.

La validación de integridad de archivos.

✅ Características
🔐 Protocolo AKE v2 con firmas digitales y RSA-2048.

📁 Cifrado de archivos mediante AES en modo CBC.

💡 Derivación segura de claves usando hash criptográfico.

🛑 Eliminación del archivo original después del cifrado.

📋 Verificación de integridad con SHA-256.

📢 Simulación clara y guiada del ataque en Colab.

🧠 Reflexión Final
El proyecto también incluye respuestas a dos preguntas de reflexión:

Estrategias de ataque para distribuir ransomware (como atacante).

Políticas de defensa para prevenir y mitigar ataques (como defensor).

👨‍🏫 Información Académica
Universidad del Norte

Departamento de Ingeniería de Sistemas y Computación

Curso de Criptografía

Entrega: 23 de mayo de 2025
