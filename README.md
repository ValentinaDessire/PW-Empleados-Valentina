# Registro de empleados

Formulario web para registrar empleados y obtener estadísticas automáticas sobre la plantilla. Los datos se guardan en un archivo JSON en el servidor.

> Práctica de la cátedra Programación Web

## Funcionalidades

- Registro de empleados: nombre y apellido, edad, estado civil, sexo y rango de sueldo.
- Validación del formulario con JavaScript.
- Tabla de resultados con todos los registros.
- Estadísticas calculadas, por ejemplo:
  - Total de empleadas mujeres.
  - Hombres casados que ganan más de 2500.
  - Mujeres viudas que ganan más de 1000.
  - Edad promedio.

## Tecnologías

`PHP` · `JavaScript` · `HTML5` · `CSS3` · `JSON`

## Estructura

```
├── index.html       # Formulario y resultados
├── formulario.js    # Validación y envío
├── formulario.php   # Guarda el empleado en empleados.json
├── results.php      # Calcula y devuelve las estadísticas
├── empleados.json   # Almacenamiento de datos
└── styles.css
```

## Cómo ejecutarlo

1. Necesitas PHP instalado (o XAMPP).
2. En la carpeta del proyecto ejecuta: `php -S localhost:8000`
3. Abre `http://localhost:8000` en el navegador.

---

Hecho por **Valentina Quintero** · [Portafolio](https://valentinadessire.github.io) · [GitHub](https://github.com/ValentinaDessire)
