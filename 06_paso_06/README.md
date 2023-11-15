# Paso 6 - Espaciado y márgenes
DEFINE MÁRGENES Y ESPACIADOS PARA GARANTIZAR QUE LOS ELEMENTOS SE
VEAN EQUILIBRADOS Y ORDENADOS EN LA PÁGINA. ESTO INCLUYE MÁRGENES
ENTRE SECCIONES, ESPACIADO ENTRE LÍNEAS Y RELLENO ALREDEDOR DE
ELEMENTOS.

## 1. DEFINE MÁRGENES EXTERIORES E INTERIORES PARA ELEMENTOS CLAVE, COMO SECCIONES, ENCABEZADOS, IMÁGENES Y PÁRRAFOS.
Los márgenes y padding en general serán dinámicos dependiendo del ancho de la pantalla. 

Tamaños habituales:
* Tamaño mínimo 2px
* Tamaño std-1 0.5rem
* Tamaño std-2 1rem
* Tamaño std-3 2rem


Se ve que los tamaños habituales tienen el mismo tamaño en ambos ejes. Existirán tamaños distintos como por ejemplo los botones, asides o ciertos párrafos donde la proporción sea distinta de 1:1

## 2. ESTABLECE UN SISTEMA DE CUADRÍCULA O REJILLA PARA ALINEAR Y DISTRIBUIR ELEMENTOS DE MANERA CONSISTENTE EN EL SITIO WEB.

Se usará principalmente dos sistemas de alineación: Flex y Grid.

El sistema con flex generalmente será con tamaños dinámicos. Se usará en sliders horizontales.

El sistema con grid principalmente se usará para organizar noticias y fotos.

La clave principal es ir jugando con ambas características para realizar el maquetado total de la web sin perder el efecto responsive.

## 3. PROPORCIONA REGLAS CLARAS SOBRE EL ESPACIADO ENTRE ELEMENTOS, COMO BOTONES, ICONOS Y BLOQUES DE CONTENIDO.

* header: max-width: 100%;
* main: max-width: 1250px;
* footer: max-width: 100%;
* span: margin-top: 40px;
* p: margin-top: 12px;
* div: margin-top: 40px;
* button: padding: 1rem 3rem;
* h1: padding: 1rem;
* h2: padding: 1rem;

Estas son las principales medidas para web. Para tablet se reducirá a la mitad y para móvil a 1/4. Si algo no termina de cuadrar mientras se genera el desarrollo consultar al departamento de UI/UX para confirmar los cambios.

## 4. CONSIDERA LA IMPLEMENTACIÓN DE MÁRGENES Y ESPACIADOS RESPONSIVOS PARA ADAPTARSE A DIFERENTES TAMAÑOS DE PANTALLA Y DISPOSITIVOS.

Desde el principio la mayoría de tamaños en la mayoría de propiedades estarán expresados en unidades de medida responsivas (rem, em, %, vw, vh, fr). En casos concretos se usarán unidades de medidas estáticas (px).
<br><br>
Como se comentó en el apartado anterior, los márgenes y espaciados dispuestos para la versión web se irán reduciendo con una relación similar a x:x^(1/2) para conseguir que la mayor información posible se mantenga y sea legible.
<br><br>
También se irá reduciendo el tamaño de las letras, imágenes, etc en función del max-width del dispositivo.

## 5. DOCUMENTA CÓMO SE APLICARÁN LOS MÁRGENES Y ESPACIADOS EN DIFERENTES SECCIONES Y PÁGINAS DEL SITIO WEB.

1. **Página de inicio:**
   - Cabecera: Margen superior de 20 píxeles, margen inferior de 20 píxeles.
   - Cuerpo principal: Margen izquierdo y derecho de 20 píxeles.
   - Secciones de noticias destacadas: Espaciado vertical de 40 píxeles entre artículos.

2. **Página de Noticias:**
   - Cabecera de noticias: Margen superior de 30 píxeles, margen inferior de 10 píxeles.
   - Listado de noticias: Espaciado vertical de 20 píxeles entre artículos.

3. **Página de Calendario de Juegos:**
   - Encabezado del calendario: Margen superior de 20 píxeles, margen inferior de 10 píxeles.
   - Filas de juegos en el calendario: Espaciado vertical de 15 píxeles entre juegos.

4. **Página de Tickets/Entradas:**
   - Cabecera de boletos: Margen superior de 40 píxeles, margen inferior de 20 píxeles.
   - Secciones de compra de boletos: Margen izquierdo y derecho de 30 píxeles.

5. **Página de Tienda:**
   - Encabezado de la tienda: Margen superior de 30 píxeles, margen inferior de 20 píxeles.
   - Espaciado entre productos: Espaciado vertical de 15 píxeles entre productos, margen izquierdo y derecho de 20 píxeles.

6. **Página de Contacto:**
   - Formulario de contacto: Margen superior de 20 píxeles, margen inferior de 20 píxeles.
   - Espaciado entre campos del formulario: Espaciado vertical de 15 píxeles entre campos.

7. **Página de Quiénes Somos:**
   - Sección de información sobre el equipo: Margen superior de 30 píxeles, margen inferior de 20 píxeles.
   - Espaciado entre miembros del equipo: Espaciado vertical de 20 píxeles entre cada miembro.

8. **Página de Blog:**
   - Cabecera del blog: Margen superior de 20 píxeles, margen inferior de 10 píxeles.
   - Espaciado entre entradas de blog: Espaciado vertical de 25 píxeles entre entradas.
