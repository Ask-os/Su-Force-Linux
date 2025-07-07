# **suForce** – su brute-forcer by **AzK-os**

**suForce** es una herramienta de fuerza bruta enfocada en contraseñas de usuarios locales del sistema Linux mediante el binario `su`. Diseñada para pruebas de seguridad en entornos controlados, esta utilidad te permite automatizar ataques de diccionario y detectar credenciales débiles en equipos con acceso físico o remoto.

---

## **Características**

- Banner personalizado estilo hacker.
- Progreso en tiempo real con porcentaje y palabra actual.
- Interfaz colorida y clara.
- Interrupción con Ctrl+C manejada elegantemente.
- Validación de argumentos y ayuda integrada.
- Código modular y fácil de modificar.

---

## 🛠️ **Uso**

```bash
./suForce -u <usuario> -w <ruta_al_diccionario>
