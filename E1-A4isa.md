```mermaid
---
config:
  themeVariables:
    xyChart:
      plotColorPalette: '#FF0000, #00FF00, #0000FF, #FFA500'
---
xychart
    title "Gráfico de la Función f(x)=(x^2+1)/147 (Colores Vibrantes)"
    x-axis "Valores de X" [1, 2, 3, 4, 5, 6]
    y-axis "Valor f(x)" 0.0 --> 0.3
    %% Las barras en rojo (#FF0000)
    bar [0.0136, 0.0340, 0.0680, 0.1156, 0.1769, 0.2517]
    %% La línea en verde (#00FF00)
    line [0.0136, 0.0340, 0.0680, 0.1156, 0.1769, 0.2517]
