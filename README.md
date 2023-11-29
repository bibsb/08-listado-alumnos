# Proyecto Lista de Alumnos con JS, React, Bootstrap y Lodash

## Estructura del Proyecto

### Componentes React

Voy a desarrollar diferentes componentes para mostrar la lista de alumnos, modal con el formulario de añadir/editar alumnos y la barra de progreso.

### Datos y Almacenamiento

Utilizaré LocalStorage para guardar y recuperar la lista de alumnos. Con YUP, aseguraré que los datos del formulario cumplan con los requisitos, como la edad mínima de 18 años.

## Lista de Alumnos

### Campos Obligatorios

- Nombre
- Apellidos
- Edad (solo mayores de 18 años)
- Curso elegido [de una lista previamente dada]
- Fecha de inscripción [en formato dd/mm/aaaa]
- Nota media alumno [número con 2 decimales]
- Porcentaje de curso completado [barra de progreso que incluya el porcentaje]

### Botones de Acción

Cada alumno tendrá botones para eliminar o editar sus datos.

## Formulario de Añadir/Editar Alumnos

### Acceso al Formulario

Un botón "Nuevo alumno" abrirá una ventana modal con el formulario para realizar la nueva alta. El formulario también se activará al editar un alumno existente.

### Ventana Modal

Utilizaré la ventana modal de Bootstrap para mantener el estilo. Esta ventana se cerrará al completar la operación o al cancelarla.

## Ordenamiento de la Lista

### Orden por Apellido por Defecto

 La lista se ordenará inicialmente por apellido,tanto de forma ascendente como descendente.

### EXTRAS: Dropdown para Cambiar el Orden

Intentaré añadir un dropdown con opciones para ordenar por curso, porcentaje completado y nota media. Tendrá la opción de elegir entre orden ascendente o descendente, otorgando flexibilidad al usuario.

## Utilización de Bootstrap y Lodash

### Bootstrap

Usaré [Bootstrap](https://getbootstrap.com/) para obtener una apariencia coherente y responsive, facilitando al usuario la gestión del listado de los alumnos.

### Lodash

Implementaré funciones de [Lodash](https://lodash.com/) para simplificar operaciones como ordenamiento y manipulación de datos, optimizando el rendimiento del código.

## Recursos Utilizados

### Frameworks y Bibliotecas

- [React](https://reactjs.org/) - Biblioteca de JavaScript para construir interfaces de usuario mediante componentes.
- [Bootstrap](https://getbootstrap.com/) - Framework de diseño que ayuda en la creación de interfaces modernas y responsive de forma rápida.
- [Lodash](https://lodash.com/) - Biblioteca de utilidades de JavaScript para simplificar operaciones complejas.

