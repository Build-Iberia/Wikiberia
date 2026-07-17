# Delimitar edificios

Dentro del servidor podrás ver que muchos edificios vienen marcados por un contorno de ladrillos en el propio terreno. Aunque estos contornos pregenerados pueden ser útiles para hacerse a la idea de la ubicación general de los edificios, es importante verificar el contorno de cada edificio para asegurarse que la proporción, rotación y posición es correcta.

Para ello, haremos uso de WorldEdit y el comando `/tpll`:

## Obtener las coordenadas en Google Maps

??

`VIDEO WEBP 1`

1. Abre Google Maps y busca la ubicación del edificio.
2. En la parte inferior izquierda, asegúrate que la vista satelital está activa (modo imagen realista) y la vista globo.
3. Acerca el cursor a la primera esquina del edificio.
4. Haz click derecho. Saldrá un cuadro de diálogo y volvemos a hacer click sobre la primera opción (aparece una numeración).
5. Se copiarán las coordenadas en formato latitud y longitud al portapapeles.

## Marca las esquinas en Minecraft

??

`VIDEO WEBP 2`

1. En el servidor de Minecraft, abre el chat y escribe el siguiente comando: `/tpll`, espacio y presiona **Ctrl + V** para pegar las coordenadas que has copiado anteriormente. Serás teletransportado a las coordenadas exactas en el servidor.
2. Marca la ubicación del bloque con un bloque de tu gusto. Puedes usar lanas de diferentes colores para determinar diferentes contornos (edificios, aceras, calles, árboles, etc.).
3. Vuelve a Google Maps y acerca el cursor a otra de las esquinas del edificio y repite la misma operación con el resto de las esquinas del edificio.

## Crear los contornos

??

`VIDEO WEBP 3`

1. En Minecraft, con el hacha de madera (usa `//wand` si no tienes el hacha o sácala del inventario de creativo), escribe el comando `//sel cuboid` para seleccionar la selección cuboidal.
2. Haz click izquierdo en una de las esquinas que has colocado con lana y click derecho en otra de las que has marcado que esté contigua a la anterior.
3. Escribe el comando `//line [bloque]`. En **[bloque]** debes escribir el nombre del bloque con el que quieres crear el contorno del edificio. Por ejemplo, usaremos lana azul clara, por lo que escribiremos `//line light_blue_wool`. De esta forma, WorldEdit creará una línea con lana azul clara coincidiendo con una de las fachadas del edificio que queremos hacer.
4. Repite esta operación con cada uno de los lados que conforman el edificio hasta conseguir un contorno cerrado.
