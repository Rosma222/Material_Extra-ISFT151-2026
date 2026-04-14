# Calculadora Web versión 02- HTML/CSS/JavaScript

##  Descripción
Calculadora web desarrollada con HTML, CSS y JavaScript. Permite realizar operaciones matemáticas básicas

##  Características
- **Operaciones básicas**: Suma, resta, multiplicación y división
- **Soporta decimales**: Punto decimal para números flotantes
- **Evalúa la expresión matemática**: Usa `eval()` función de Javascript para evaluar expresiones
- Usa concatenación de strings (+=)


## Estructura
El código está organizado en tres capas principales dentro de un único archivo:

1. HTML = Estuctura
Utiliza una **tabla** como elemento principal:

```html
<table>
  <tr>
    <td >
      <input>
    </td>
  </tr>
</table>
```

2. CSS = Estilo
Estilos Generales, tabla y botones de colores.
Botones con efectos 3D y colores diferenciados:
- Azul = Números (0-9) y punto 
- Verde = Operaciones (+, -, *, /) 
- Naranja = Resultado (=)
- Rojo = Borrar 

3. JavaScript = Lógica
Patrón de Diseño: Event Handler con asignación directa:

```function main() {
    btn0.onclick = onBtn0Click;
    btn1.onclick = onBtn1Click;
    // ...
}
window.onload = main;
```


### Secuencia

│Click en Botón│ > │Función onBtn..Click│ > │Agregar al display│ > │Mostrar resultado│
