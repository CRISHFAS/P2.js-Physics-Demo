# P2.js Physics Demo

Una demostración minimalista del motor de física 2D **p2.js** con renderizado WebGL.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![P2.js](https://img.shields.io/badge/p2.js-0.7.1-green.svg)

## Descripción

Simulación de física 2D en tiempo real que muestra las capacidades básicas de p2.js:
- Cuerpos rígidos dinámicos
- Colisiones realistas
- Gravedad y fuerzas
- Renderizado WebGL de alto rendimiento

## Características

- **Motor de física realista** con p2.js
- **Renderizado WebGL** fluido y eficiente
- **Controles nativos integrados** (Open/Close Controls)
- **Configuración optimizada** del solver físico
- **Sin dependencias externas** excepto p2.js
- **Responsive** y compatible con dispositivos móviles

## Demo en Vivo

[Ver Demo](https://tu-usuario.github.io/p2js-physics-demo)


### Controles Nativos

Los controles de p2.js aparecen automáticamente en la esquina superior derecha:

- **Open Controls**: Muestra panel de configuración
- **Close Controls**: Oculta el panel
- **Play/Pause**: Controla la simulación
- **Physics Settings**: Ajusta gravedad, iteraciones, etc.

## Configuración Física

```javascript
world.gravity = [0, -10];           // Gravedad (m/s²)
world.solver.iterations = 20;       // Precisión de cálculos
world.solver.tolerance = 0.01;      // Tolerancia de error
world.setGlobalStiffness(1e4);      // Rigidez de contactos
world.solver.frictionIterations = 10; // Iteraciones de fricción
```

## Tecnologías

- [p2.js](https://github.com/schteppe/p2.js) - Motor de física 2D
- WebGL - Renderizado acelerado por hardware
- HTML5 Canvas - Fallback de renderizado

## Recursos

- [Documentación oficial de p2.js](http://schteppe.github.io/p2.js/docs/)
- [Ejemplos de p2.js](https://github.com/schteppe/p2.js/tree/master/examples)
- [Tutorial de física 2D](https://gamedevacademy.org/introduction-to-p2-js/)

## Agradecimientos

- [Stefan Hedman](https://github.com/schteppe) - Creador de p2.js
- La comunidad de p2.js por los ejemplos y documentación
