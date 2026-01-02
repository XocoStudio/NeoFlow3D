# 🚀 NeoFlow 3D - Guía del Usuario
![NeonFlow]( NeonFlow.jpg "Preview NeonFlow")



¡Bienvenido a **NeoFlow 3D**! Esta aplicación es un estudio de diseño 3D todo en uno donde puedes dibujar, modelar y crear escenas impresionantes de forma intuitiva.
![Preview of NeonFlow user interface](CapturaNeonFlow.jpg "Preview of NeonFlow")

Aquí tienes un resumen de todo lo que puedes hacer:

## 🎨 Herramientas de Dibujo y Creación
NeoFlow te permite pasar de bocetos simples a formas complejas rápidamente:
- **Dibujo Libre y Curvas**: Crea trazos naturales, líneas precisas o tubos 3D con grosor ajustable.
- **Biblioteca de Figuras**: Inserta instantáneamente círculos, rectángulos, estrellas, hexágonos y más.
- **Pintor de Vóxeles**: Construye bloques por bloques al estilo de cuadrícula para diseños rápidos o arte digital.
- **Figuras Primitivas**: Crea volúmenes básicos como cubos, esferas, cilindros y planos con un solo clic.

## 🛠️ Herramientas de Edición Avanzada
Si necesitas más detalle, NeoFlow incluye potentes herramientas de modelado:
- **Edición de Malla (Mesh Edit)**: Selecciona vértices, aristas o caras para estirar, subdividir y esculpir la forma exacta que deseas.
- **Transformación Directa**: Mueve, rota y escala cualquier objeto con controles visuales fáciles de usar.
- **Simetría y Repetición**: 
    - **Espejo (Mirror)**: Duplica tus diseños simétricamente.
    - **Radial**: Crea patrones circulares.
    - **Matriz (Matrix)**: Genera cuadrículas de objetos.
    - **A lo largo de un Camino**: Distribuye copias de un objeto siguiendo una línea curva.

## 🌈 Diseño y Apariencia
Haz que tus creaciones se vean profesionales:
- **Estudio de Pinceles**: Personaliza el grosor, el color, la opacidad y añade efectos de resplandor (Glow).
- **Biblioteca de Colores**: Elige entre paletas prediseñadas o crea tu propio color personalizado.
- **Capas (Layers)**: Organiza tu trabajo en capas para ocultar, bloquear o gestionar diferentes partes del proyecto por separado.

## 📐 Precisión y Medición
Para los que buscan exactitud:
- **Snap y Guías**: Tus trazos se ajustarán automáticamente a la cuadrícula o a los puntos finales de otros objetos.
- **Herramientas de Medición**: Añade dimensiones, mide radios o ángulos directamente en la escena.
- **Vistas de Cámara**: Cambia rápidamente entre vista superior, frontal, lateral o perspectiva.

## 🌌 Entorno y Visualización
Crea la atmósfera perfecta:
- **Fondos Personalizados**: Sube imágenes de alta calidad (HDRI) para iluminar tu escena o elige colores de fondo.
- **Cielo Estrellado**: Activa un fondo nocturno con miles de estrellas para proyectos espaciales.
- **Plataforma Giratoria (Turntable)**: Haz que tu modelo gire automáticamente para presentarlo como un producto de lujo.

## 💾 Gestión de Proyectos
- **Historial**: Deshaz y rehace cualquier cambio con total libertad.
- **Exportación**: Cuando termines, descarga tu modelo en formato **OBJ, STL, GLTF o FBX** para usarlo en otras aplicaciones o imprimirlo en 3D.
- **Scripts**: Para los usuarios más avanzados, permite ejecutar pequeñas acciones automáticas para ahorrar tiempo.

---
*¡Empieza a crear hoy mismo con NeoFlow 3D!*


# Manual de Usuario: NeoFlow 3D

NeoFlow 3D es una herramienta avanzada de diseño y modelado 3D basada en la web, diseñada para ser intuitiva pero potente, permitiendo desde dibujos simples hasta scripts complejos y modelado poligonal detallado.

## 1. Navegación y Visualización

### Controles de Cámara (Ratón y Teclado)
*   **Orbitar:** Mantén presionado el botón izquierdo del ratón y arrastra.
*   **Panorámica (Pan):** Mantén presionado el botón derecho del ratón (o Shift + botón izquierdo) y arrastra.
*   **Zoom:** Usa la rueda del ratón hacia arriba o hacia abajo.
*   **W/A/S/D:** Movimiento de cámara (estilo primera persona).
*   **Q/E:** Elevar o descender la cámara.

### Atajos Globales de Teclado
*   **Espacio:** Mostrar/Ocultar todos los paneles de la interfaz (UI).
*   **Escape:** Cancelar la acción actual, deseleccionar objetos o volver al modo de vista.
*   **Suprimir / Backspace:** Eliminar el objeto o línea seleccionada.
*   **Shift + R:** Restablecer el diseño de las ventanas a su posición original.
*   **Enter:** Finalizar el trazado de una ruta o línea (en modos de dibujo).

## 2. Herramientas de Dibujo y Modelado

### Modos de Dibujo
*   **Draw (Lápiz):** Trazado libre de líneas.
*   **Spline:** Curvas suaves basadas en puntos de control.
*   **Polyline:** Secuencia de segmentos de línea rectos.
*   **Tube:** Crea geometrías tubulares 3D a lo largo de un camino.
*   **Shapes:** Formas predefinidas como rectángulos, círculos, estrellas, corazones, etc.

### Modelado Poligonal (Poly Edit)
Permite una edición detallada de mallas. Al seleccionar un modelo y entrar en **Poly Edit**, puedes manipular:
*   **Vértices:** Puntos individuales de la malla.
*   **Aristas:** Líneas que conectan vértices.
*   **Caras:** Superficies planas de la malla.
Operaciones comunes incluyen **Extruir**, **Subdividir** y **Transformar**.

### Pintado Voxel (Voxel Painter)
Permite "pintar" bloques 3D (voxels) en el espacio o sobre objetos existentes.
*   **Click:** Añadir un voxel.
*   **Shift + Click:** Eliminar un voxel.

## 3. Línea de Comandos y Scripts

### Línea de Comandos
Ubicada en la parte inferior, permite introducir comandos rápidos para precisión:
*   **Distancia:** Introduce un número (ej. `10`) para definir la longitud del siguiente segmento.
*   **Ángulo:** Usa el formato `distancia<ángulo` (ej. `5<45`) para dibujar con exactitud matemática.

### Editor de Scripts
Permite ejecutar código JavaScript directamente para manipular la escena. Ideal para generar patrones algorítmicos o automatizar tareas repetitivas.

*   **API Interna:** El editor proporciona acceso a tres variables principales:
    *   `lines`: Un array con todos los objetos de línea actuales.
    *   `setLines(newLines)`: Función para actualizar la escena con un nuevo array de líneas.
    *   `THREE`: La librería Three.js completa para cálculos matemáticos y vectores.
*   **Ejemplo rápido:**
    ```javascript
    const newLine = {
      id: "mi-script-line",
      points: [new THREE.Vector3(0,0,0), new THREE.Vector3(5,5,5)],
      color: "#ff0000",
      width: 2,
      type: "polyline",
      layerId: "layer-1"
    };
    setLines([...lines, newLine]);
    ```

## 4. Gestión de Escena

### Capas (Layers)
Organiza tu trabajo por capas. Puedes bloquearlas para evitar cambios accidentales o ocultarlas para despejar la vista.

### Propiedades y Estilos
Ajusta color, grosor de línea, opacidad y brillo (Glow) desde el panel de **Properties**. NeoFlow incluye una **Color Library** con paletas diseñadas profesionalmente.

### Ayudas de Dibujo
*   **Snap (Imán):** Ajusta los puntos a extremos, puntos medios o al centro de círculos.
*   **Ortho:** Restringe el movimiento a ángulos rectos (90°).
*   **Grid Settings:** Personaliza el tamaño, color y visibilidad de la cuadrícula base.

---
*Manual generado para NeoFlow 3D - Flujo de trabajo Creativo y Técnico.*

