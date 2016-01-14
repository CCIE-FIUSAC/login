# login
Página personalizado de inicio de sesión para Moodle

Contiene archivos modificados del código base de Moodle.
## Archivos
* **index_form.html** es la página de inicio de sesión. Reside dentro de la carpeta `/login `.

* **outputrenderers.php** es la librería modificado para renderizar el enlace de inicio de sesión. Reside dentro de la carpeta `/lib`.

## Instalación
Copiar archivos con SSH, ejemplo:
```bash
scp index_form.html elearningdevwww:/var/www/campus/login/
scp outputrenderers.php elearningdevwww:/var/www/campus/lib/
```
