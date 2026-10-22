# digital-assets

Repositorio de Shameless Company para el diseno, modelado y publicacion de recursos graficos 2D, modelos 3D y plantillas tecnicas para tiendas digitales.

## Objetivo del repositorio
Crear activos digitales que se puedan vender en plataformas como la tienda Fab de Epic Games, itch.io, Payhip o Amazon KDP. La meta es producir paquetes pequenos pero bien terminados que no requieran costo de mantenimiento ni servidores para generar ingresos constantes.

---

## Ideas de proyectos y requisitos de MVP

### 1. Packs 3D low poly con paleta de color fija
- Que es: Modelos 3D simples de objetos o escenarios para videojuegos que usan una sola imagen pequeña como paleta de colores en lugar de texturas pesadas individuales.
- Como genera dinero: Se suben a la tienda Fab de Epic Games (que paga el 88% de cada venta) y a itch.io para desarrolladores de juegos indie.
- Requisitos de MVP:
  1. Conjunto de 15 a 25 modelos de una misma categoria (por ejemplo: objetos de oficina o herramientas de taller) con menos de 1,000 triangulos por pieza.
  2. Una sola textura PNG de 256x256 pixeles donde esten ordenados los colores del paquete.
  3. Exportar todos los modelos en formato .glb y .fbx con su punto de origen centrado en la base.

### 2. Packs 2D pixel art de interfaz y tilesets
- Que es: Botones, barras de estado, casillas de inventario y fondos cuadriculados dibujados en pixel art para proyectos de juegos clasicos.
- Como genera dinero: Venta directa en itch.io y Payhip (el plan gratuito cobra solo el 5% por venta).
- Requisitos de MVP:
  1. Hoja de sprites con al menos 20 elementos de interfaz listos para recortar (botones en reposo y presionados, bordes de ventanas, iconos).
  2. Archivos en PNG transparente mas el archivo editable en Aseprite o LibreSprite.
  3. Una imagen de muestra que ensene como se ven colocados los elementos en una pantalla de juego real.

### 3. Loops de video 4K abstractos
- Que es: Animaciones de 5 a 10 segundos en bucle continuo (tubos de luz, movimientos geometricos, particulas) renderizadas en resolucion 4K.
- Como genera dinero: Vender las licencias de uso en bancos de video como Adobe Stock y Pond5 para que las usen en fondos de anuncios o videos corporativos (pagan entre 20 y 80 dolares por descarga).
- Requisitos de MVP:
  1. Escena en Blender donde el primer fotograma y el ultimo conecten sin saltos visuales.
  2. Render a resolucion 3840x2160 a 60 cuadros por segundo en formato MP4 o ProRes.
  3. Sacar 3 variaciones de color o velocidad a partir del mismo archivo para publicar un pequeno lote.

### 4. Cuadernos tecnicos en Amazon KDP
- Que es: Libros de notas impresos bajo demanda por Amazon con interiores pensados para tareas tecnicas (bitacoras de servidores, registro de overclocking, diseno de niveles).
- Como genera dinero: Amazon se encarga de la impresion y envio del libro fisico. Las regalias mensuales se transfieren en dolares a la cuenta de Payoneer sin costo inicial.
- Requisitos de MVP:
  1. Archivo PDF de 120 paginas en tamano 6x9 pulgadas con la cuadricula y campos de texto repetidos en limpio.
  2. Portada completa en PDF a 300 puntos por pulgada con el tamano del lomo exacto para esa cantidad de paginas.
  3. Dar de alta el producto en Amazon KDP con su descripcion y precio en dolares.

### 5. Mods y recursos para juegos
- Que es: Complementos para juegos populares, como comodines nuevos para Balatro, skins de armas para Counter-Strike o bases de personajes para creadores virtuales.
- Como genera dinero: Venta de los archivos en Payhip, comisiones para comunidades de jugadores o postulacion en el Steam Workshop.
- Requisitos de MVP:
  1. En Balatro: 1 comodin funcionando con su archivo en Lua y su dibujo a 71x95 pixeles compatible con Steamodded.
  2. En modelos virtuales: Base de cuerpo humano o anime con huesos y expresiones faciales basicas exportado en archivo .vrm.
  3. Guia de texto corta explicando en que carpeta pegar el archivo para que el usuario no se pierda.
