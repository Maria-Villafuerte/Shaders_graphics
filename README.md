# Planet Shader System

Este proyecto implementa un sistema de renderizado de planetas en Rust, permitiendo la visualización de diferentes tipos de planetas con efectos de sombreado únicos. El sistema utiliza shaders personalizados para crear representaciones visuales realistas de planetas con diferentes características superficiales.

## Descripción

En este trabajo, se ha utilizado Rust para implementar un sistema de renderizado de planetas, empleando técnicas de sombreado avanzadas para crear efectos visuales realistas. El sistema incluye múltiples variaciones de planetas tipo Tierra, cada uno con características únicas de superficie y atmósfera.

### Características

- **Implementación en Rust**: Sistema de renderizado eficiente y de alto rendimiento.
- **Shaders Personalizados**: Incluye shaders para diferentes tipos de planetas:
  - Tierra Tropical: Océanos turquesa y masas terrestres vibrantes
  - Tierra Congelada: Extensas capas de hielo y océanos fríos
  - Tierra Desértica: Mundo dominado por dunas y formaciones rocosas
  - Tierra Oceánica: Planeta cubierto de agua con diferentes profundidades
  - Tierra Selvática: Densos bosques y vegetación abundante
  - Tierra Volcánica: Superficie activa con flujos de lava
  - Tierra Primordial: Representación del planeta en sus primeras etapas
- **Efectos Dinámicos**: Incluye efectos de iluminación, atmósfera y animaciones.
- **Controles Interactivos**: Permite cambiar entre diferentes tipos de planetas.

## Uso

Para ejecutar el programa, asegúrate de tener Rust instalado en tu sistema. Luego, clona este repositorio y ejecuta:

```bash
git clone https://github.com/Maria-Villafuerte/Shaders_graphics.git
cd planet-shader-system
cargo build
cargo run
```

## Controles

- **Teclas 1-7**: Cambia entre diferentes tipos de planetas
- **Flechas**: Rotar la vista
- **W/S**: Acercar/Alejar la cámara
- **A/D**: Mover la cámara lateralmente
- **Q/E**: Mover la cámara verticalmente

## Sistema de Shaders

Cada planeta utiliza un shader personalizado que define:
- Colores base para diferentes tipos de terreno
- Efectos atmosféricos
- Patrones de superficie usando ruido procedural
- Efectos de iluminación dinámicos

## Demo

Aquí puedes ver una demostración del sistema en funcionamiento:

![Demo GIF](./planets.gif)

## Requisitos del Sistema

- Rust (última versión estable)
- Dependencias:
  - minifb
  - nalgebra-glm
  - fastNoise-lite


