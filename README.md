# Inmobiliaria
Aplicación web básica para la gestión de un portal inmobiliario.

## 🧰 Tecnologías
- HTML, CSS, JavaScript
- PHP (backend)
- MySQL (base de datos)
- Estructura de carpetas:
  - `/html` → archivos frontend
  - `/css` → estilos
  - `/fuente` → fuentes tipográficas
  - `/img` → imágenes
  - `index.html` → página de inicio
  - `linkRef.txt` → referencias de enlaces

## 📝 Funcionalidades
- Presentación de inmuebles para venta o alquiler.
- Navegación básica por categorías o zonas.
- Formulario de contacto para interesados.
- Estilos responsivos (o adaptados) para mostrar en distintos dispositivos.

## 📂 Estructura de carpetas
```
inmobiliaria/
├─ css/
├─ fuente/
├─ html/
├─ img/
├─ index.html
├─ linkRef.txt
└─ README.md
```

## 🚀 Cómo usar
1. Clona el repositorio:
   ```bash
   git clone https://github.com/carmonaa0116/inmobiliaria.git
   ```
2. Abre `index.html` en tu navegador para ver la página principal.
3. Si quieres extenderla:
   - Añade archivos en `/html` para nuevas secciones.
   - Ajusta estilos en `/css`.
   - Sustituye imágenes en `/img`.
4. Si la conviertes en una aplicación con backend (PHP + MySQL): configura el servidor local (por ejemplo con XAMPP) y ajusta las conexiones a la base de datos.

## ✔️ Buenas prácticas
- Organiza bien los estilos: muestra lógica de clases reutilizables.
- Mantén los nombres de archivos descriptivos (por ejemplo: `inmueble-gran_tenerife.html`).
- Si usas PHP/MySQL en el futuro, asegúrate de usar consultas preparadas para evitar inyección SQL.
- Versiona los cambios con commits claros: “añadida sección contacto”, “mejorados estilos responsivos”, etc.

## 🔧 Próximos pasos / mejoras sugeridas
- Integrar backend (PHP + MySQL) para que los inmuebles se gestionen dinámicamente desde la base de datos.
- Añadir panel de administración para dar de alta, modificar o eliminar inmuebles.
- Implementar filtrado por zona, precio, tipo de inmueble.
- Añadir autenticación de usuarios (ej: agentes, administradores).
- Hacer el sitio totalmente responsive para móviles y tablets.
- Mejorar la accesibilidad: etiquetas `alt` en imágenes, buen contraste de colores, navegación teclado.
- Subir a un hosting real y usar dominio propio.

## 🤝 Colaboración
¡Las contribuciones son bienvenidas! Si quieres colaborar:
1. Haz un *fork* del proyecto.
2. Crea una rama (`git checkout -b feature/nueva-función`).
3. Haz tus cambios y *commits*.
4. Envía un *pull request* para revisión.

## 📜 Licencia
Este proyecto está bajo la licencia MIT (o especifica la que prefieras).

---

¡Gracias por visitar el repositorio! Si tienes sugerencias, dudas o mejoras que aportar, no dudes en abrir un **Issue** o enviarme un **Pull Request**.
