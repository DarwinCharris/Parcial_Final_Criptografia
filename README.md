# 🛡️ Simulación de Ransomware – Examen Final de Criptografía

## 📚 Descripción

Este proyecto es una **simulación académica** de un ataque de ransomware, desarrollado como examen final del curso de Criptografía de la Universidad del Norte. La simulación implementa los componentes clave de un ransomware real, pero de forma segura y controlada en un entorno educativo.

> ⚠️ **Advertencia**: Este proyecto es únicamente con fines educativos. El uso indebido de técnicas criptográficas para crear malware real es ilegal y está penado por la ley.

---

## 🧪 Contenido del Proyecto

- `ransomware_simulado.ipynb`: Contiene toda la lógica del ransomware simulado, incluyendo:
  - Generación de certificados digitales RSA (2048 bits) para atacante y víctima.
  - Implementación del protocolo de intercambio de claves **AKE v2**.
  - Derivación de clave simétrica mediante **KDF (SHA-256)**.
  - Cifrado de archivos con **AES-256-CBC**.
  - Simulación de la notificación al usuario afectado.
  - Recuperación de archivos cifrados tras el pago simulado.
  - Verificación de integridad de los archivos con **SHA-256**.

---

## ⚙️ Requisitos

- [PyCryptodome](https://pypi.org/project/pycryptodome/)
- Google Colab (recomendado para ejecutar)

### Instalación de dependencias (si lo ejecutas localmente)

```bash
pip install pycryptodome
