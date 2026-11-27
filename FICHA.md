# Ficha de mi aplicación · Hito 0
 
- **Alumno/a:** Antonio Miguel Ferres Torres
- **Temática:** Anime (AnimeTeca: cada usuario guarda su colección de animes favoritos)
- **Qué gestiona:** Animes
## Campos
 
| # | Campo | Tipo de dato | Componente | Ejemplo de valor / opciones |
|---|-------|--------------|------------|-----------------------------|
| 1 | Título | texto | campo de texto | Naruto Shippuden |
| 2 | Estudio | texto | campo de texto | Studio Pierrot |
| 3 | Año de estreno | entero | selector numérico | 2007 (de 1960 a 2026) |
| 4 | Nº de episodios | entero | selector numérico | 500 (de 1 en adelante) |
| 5 | Mi nota | decimal | campo de texto | 8,5 (de 0 a 10) |
| 6 | Género | lista | lista desplegable | Shōnen / Shōjo / Seinen / Isekai / Mecha / Fantasía / Ciencia ficción / Deportes / Slice of life / Terror |
| 7 | Estado | opción | botones de opción | Viendo / Terminado / Pendiente |
| 8 | Lo recomiendo | sí/no | casilla | sí |
 
Obligatorios (marcados con `*`): Título, Género y Estado.
 
## Pantallas
 
| Pantalla | Foto |
|----------|------|
| Inicio de sesión | `bocetos/1_inicio_sesion.png` |
| Ventana principal | `bocetos/2_ventana_principal.png` |
| Formulario de alta | `bocetos/3_formulario.png` |
 
### Ventana principal
 
- **Menús y sus opciones:**
  - Archivo: Cerrar sesión, Salir
  - Animes: Añadir anime…, Editar anime…, Eliminar anime
  - Ayuda: Acerca de AnimeTeca
- **Columnas de la tabla:** Título, Género, Mi nota, Estado
### Qué hace cada botón
 
- Inicio de sesión › **Entrar** (o tecla Intro): comprueba el usuario y la contraseña y abre la ventana principal. **Salir**: cierra la aplicación. **Regístrate**: de momento muestra «Disponible próximamente.»
- Ventana principal › **Añadir anime**: abre el formulario de alta vacío. **Editar** (o doble clic en una fila): abre el formulario con los datos del anime seleccionado. **Eliminar** (separado de los demás): pide confirmación y borra el anime seleccionado. El buscador filtra la tabla por título mientras escribes.
- Formulario › **Guardar**: comprueba los campos obligatorios, guarda el anime, cierra la ventana y lo añade a la tabla. **Cancelar**: cierra sin guardar.
### Mensajes
 
- Si el usuario o la contraseña están mal: «El usuario o la contraseña no son correctos.»
- Si falta el usuario o la contraseña: «Escribe el usuario y la contraseña.»
- Si falta un campo obligatorio en el formulario: «Rellena los campos marcados con *.»
- Si la nota no es válida: «La nota debe ser un número entre 0 y 10 (por ejemplo, 7,5).»
- Si se pulsa Editar o Eliminar sin elegir fila: «Selecciona un anime de la tabla.»
- Al eliminar: «¿Seguro que quieres eliminar "Naruto Shippuden"? No se puede deshacer.» con los botones [Eliminar] y [Cancelar].
 