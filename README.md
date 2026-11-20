# Simulador del robot de tenis de mesa

Interfaz web del robot lanzador (firmware **4.11**), en modo simulación.
No necesita el robot: los datos de la pantalla son de demostración.

## Ver el simulador

- **En GitHub Pages:** abre la dirección de la página de este repositorio.
- **En tu computador:** descarga el repositorio y abre `index.html` en Chrome, Edge o Firefox.

## Qué puedes probar

- **Inicio:** tipo de tiro (efecto, distancia e intensidad), velocidad, efecto y RPM por rodillo.
- **Lanzamientos:** calculadora de RPM, tabla de velocidad y efecto, y puntos de caída por programa.
- **Entrenamiento:** biblioteca de 83 ejercicios, editor de ejercicios (tipo de tiro en tres desplegables,
  "Aplicar config. de la bola 1 a todas"), Tercera bola y práctica por tiempo y series.
- **Ajustes:** oscilación del servo (rango y periodo), posiciones derecha, centro y revés,
  pruebas por componente y últimos mensajes.

## Qué no hace el simulador

- No se conecta a ningún robot ni mueve ningún motor.
- No guarda datos en el robot. Los ajustes que cambies se guardan solo en tu navegador.
- Los sensores, encoders y el servo son simulados: sus valores no reflejan el hardware real.

## Estructura

- `index.html`: la interfaz completa, en un solo archivo (HTML, CSS y JavaScript).
- `.nojekyll`: indica a GitHub Pages que no procese el sitio con Jekyll.

## Publicar en GitHub

1. Crea un repositorio nuevo en GitHub (por ejemplo `simulador-robot-tenis`).
2. Sube estos archivos, incluido `.nojekyll`.
3. Ve a **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. En unos minutos la dirección aparece en la misma pantalla.
