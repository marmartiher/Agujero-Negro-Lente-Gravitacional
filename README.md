# Agujero-Negro-Lente-Gravitacional
Agujero Negro Lente Gravitacional
🖥️ #MiniSimulador – Agujero Negro - Lente Gravitacional y Disco de Acreción
Herramienta IA: DeepSeek
Prompt principal: **Objetivo:** Crear un simulador físico-visual de agujero negro interactivo con HTML/CSS/JavaScript en un solo archivo que funcione en local y que incluya efectos realistas y optimización responsive.
**Requisitos clave:**
1. Simulación física de:
   - Lente gravitacional (anillos concéntricos)
   - Disco de acreción con partículas orbitales
   - Radiación de Hawking
   - Horizonte de eventos
   - Estrellas VISIBLES dentro del agujero negro
2. Elementos visuales obligatorios:
   - Fondo estrellado con animación CSS
   - Panel superior con datos en tiempo real (masa, radio)
   - Controles deslizantes para masa (2-50 M☉), velocidad y partículas
   - Efecto Doppler en colores de partículas (azul/blanco cerca del centro, rojo/naranja en bordes)
**Funciones JavaScript requeridas:**
1. Genera estrellas de fondo responsive
2. Clase `AgujeroNegro` con:
- Inicializa partículas con propiedades orbitales
- Asigna colores basados en temperatura y posición
- Calcula movimiento orbital y pérdida energética
- Renderiza partículas con núcleo + halo luminoso
- Círculo con borde difuminado
- Anillos de distorsión espaciotemporal
- Partículas aleatorias cerca del horizonte
- estrellas internas con rotación lenta
- Secuencia de renderizado
- Sliders: Masa, Velocidad, Partículas y botón Reset.
// DATOS FÍSICA:
"Velocidad orbital: Math.sqrt(mass/radius) - Kepler adaptado"
"Pérdida energía: radio -= 0.0005 * speed (espiral hacia centro)"
"Radiación Hawking: más intensa en masas pequeñas (coef 0.3 vs 0.1)"
// EFECTOS VISUALES:
Horizonte SEMI-TRANSPARENTEpara estrellas internas"
Orden renderizado: 1) Lente 2) Disco 3) ★ Estrellas internas ★ 4) Horizonte
Color partículas: Temperatura inversa a radio (HSL: 220°azul → 0°rojo)
Halo estelar:h Gradiente radial núcleo blanco → transparente
