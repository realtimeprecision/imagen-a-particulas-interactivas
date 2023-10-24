# Imágen a particulas interactivas.

## Descripción
Este proyecto utiliza una combinación de bibliotecas para generar una experiencia visual interactiva. Se basa en `jQuery`, `pixi.js`, y scripts personalizados para lograr esta interacción.

## Dependencias
- [jQuery 2.2.4](https://cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js)
- [pixi.js 4.1.1](https://cdnjs.cloudflare.com/ajax/libs/pixi.js/4.1.1/pixi.min.js)
- `animationFrame.js` (local)
- `nodes.js` (local)

## Funcionalidades
Se utiliza una función `lowPerformance` para determinar si el dispositivo es de baja potencia (por ejemplo, móviles). También hay un script para inicializar nodos con una imagen y propiedades específicas.

## Cómo usar
Para incorporar este proyecto en tu página web, simplemente añade el siguiente código de `iframe` en el lugar donde desees mostrarlo:

```html
<iframe src="https://example.com/particulas/" frameborder="0" style="width: 100%; height: 100%;"></iframe>
\```

Suponiendo que hayas subido este proyecto en un directorio llamado `particulas`.

Para cambiar la imagen, simplemente agrégala al directorio `/img/` y luego asígnala a la propiedad `drawnImage` de la función `Nodes.multipleInit`.

---
Desarrollado por **Real Time Precision**
