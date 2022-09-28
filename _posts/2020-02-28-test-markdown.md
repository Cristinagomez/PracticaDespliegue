---
layout: post
title: Práctica 1 - Despliegue de una web estática
subtitle: Proceso de elaboración de la práctica
tags: [test]
comments: true
---

Este es un post de demostración para mostrarte cómo escribir entradas de blog con markdown.  Te recomiendo encarecidamente que [te tomes 5 minutos para aprender a escribir en markdown](https://markdowntutorial.com/) - te enseñará a transformar el texto normal en negrita/itálica/títulos/tablas/etc.

**Aquí hay un texto en negrita**

## Aquí hay un encabezado secundario

Aquí hay una tabla inútil:

| Número | Siguiente número | Número anterior |
| :------ |:--- | :--- |
| Cinco | Seis | Cuatro |
| Diez | Once | Nueve |
| Siete | Ocho | Seis |
| Dos | Tres | uno |


¿Qué tal un delicioso crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

¡También se puede centrar!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Aquí hay un trozo de código:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

Y aquí está el mismo código con resaltado de sintaxis:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

Y aquí está el mismo código de nuevo pero con números de línea:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Cajas
Puede añadir cajas de notificación, advertencia y error de esta manera:

### Notificación

{: .box-note}
**Note:** Esta es una caja de notificación.

### Warning

{: .box-warning}
**Warning:** Esta es una caja de advertencia.

### Error

{: .box-error}
**Error:** Esta es una caja de error.
