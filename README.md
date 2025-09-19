# Comunicación con Markdown

Esta guía presenta los principales comandos de Markdown para formatear texto de manera efectiva.

## Encabezados

```markdown
# Encabezado 1
## Encabezado 2  
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```

## Formato de Texto

### Énfasis
```markdown
*cursiva* o _cursiva_
**negrita** o __negrita__
***negrita y cursiva*** o ___negrita y cursiva___
~~tachado~~
```

Resultado:
- *cursiva* o _cursiva_
- **negrita** o __negrita__
- ***negrita y cursiva*** o ___negrita y cursiva___
- ~~tachado~~

## Listas

### Lista no ordenada
```markdown
- Elemento 1
- Elemento 2
  - Subelemento
  - Otro subelemento
- Elemento 3
```

### Lista ordenada
```markdown
1. Primer elemento
2. Segundo elemento
   1. Subelemento
   2. Otro subelemento
3. Tercer elemento
```

## Enlaces e Imágenes

### Enlaces
```markdown
[Texto del enlace](https://www.ejemplo.com)
[Enlace con título](https://www.ejemplo.com "Título del enlace")
```

### Imágenes
```markdown
![Texto alternativo](url-de-la-imagen.jpg)
![Logo](https://ejemplo.com/logo.png "Título de la imagen")
```

## Código

### Código en línea
```markdown
Usa `código en línea` para resaltar palabras clave.
```

### Bloques de código
````markdown
```javascript
function saludar() {
    console.log("¡Hola mundo!");
}
```
````

## Tablas

```markdown
| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Dato 1    | Dato 2    | Dato 3    |
| Dato 4    | Dato 5    | Dato 6    |
```

## Citas

```markdown
> Esta es una cita.
> 
> Puede tener múltiples párrafos.
>> Y citas anidadas.
```

## Líneas y Separadores

### Línea horizontal
```markdown
---
```

### Salto de línea
```markdown
Primera línea  
Segunda línea (dos espacios al final de la línea anterior)
```

## Enlaces de Referencia

```markdown
[Texto del enlace][1]
[Otro enlace][referencia]

[1]: https://www.ejemplo.com
[referencia]: https://www.github.com "GitHub"
```

## Escape de Caracteres

Para mostrar caracteres especiales literalmente, usa la barra invertida `\`:

```markdown
\*Este texto no estará en cursiva\*
\# Este no será un encabezado
```
