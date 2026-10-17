# MANT-IA — Miniweb de presentación

Página estática desarrollada con HTML, CSS y JavaScript. No requiere instalar paquetes ni ejecutar un proceso de compilación.

## Abrir en tu computadora
1. Extrae el ZIP.
2. Abre `index.html` con Chrome, Edge o Firefox.
3. Prueba el cálculo, los ejemplos y la navegación.

## Archivos
- `index.html`: página completa, diseño y calculadora.
- `README.md`: instrucciones del proyecto.

## Publicación prevista
Sube estos archivos a la raíz de un repositorio de GitHub. Después importa ese repositorio en Vercel como un proyecto estático, sin compilación. La página de entrada es `index.html`. Los nombres y opciones concretos de la interfaz deben verificarse al hacer la publicación.

Este paquete todavía no está subido a GitHub ni desplegado en Vercel.

## Alcance
La web presenta el proyecto y contiene una simulación local. No conecta con Google Forms, Sheets, Make, Excel, ni con cuentas reales. No recopila ni persiste datos. El estado del proyecto es una descripción proporcionada por su autor, no una consulta en tiempo real.

La calculadora usa HH = duración × personas y supone igual duración para todos. Si las duraciones individuales difieren, se deben sumar las horas individuales. Sus límites (duración mayor que 0 y hasta 24 horas; 1–100 personas enteras) son ilustrativos, no una réplica del escenario Make. El resultado se muestra con hasta dos decimales.

## Validación
Se revisaron los cálculos base, los límites y el rechazo de valores inválidos mediante ejecución de JavaScript. La revisión visual en navegador queda pendiente.
