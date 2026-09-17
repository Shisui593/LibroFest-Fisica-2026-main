# 🚀 Simulador Interactivo MRU - LibroFest 2026
> **Física Básica & Ciencias de la Computación**

Recurso digital interactivo desarrollado para la feria académica **LibroFest**, enfocado en el modelado del **Movimiento Rectilíneo Uniforme (MRU)** y su relación con el desarrollo de software, videojuegos y robótica.

---

## 🌟 Características Principales

- **🎮 Simulación en Tiempo Real (Canvas 2D):**
  - Pista graduada milimétricamente con marcas dinámicas.
  - Selección de 4 vehículos/móviles: *Auto Deportivo, Rover Marciano, Dron Autónomo y Partícula Cuántica*.
  - Vector de velocidad dinámico ($\vec{v}$) con magnitud y sentido en tiempo real.
  - Marcas estroboscópicas de tiempo ($t$).
- **📈 Gráficas Sincronizadas en Vivo:**
  - Gráfica $x(t)$ (Posición vs Tiempo) con cálculo visual de la **pendiente ($m = v$)**.
  - Gráfica $v(t)$ (Velocidad vs Tiempo) con **área sombreada bajo la curva ($\text{Área} = \Delta x$)**.
- **📊 Telemetría y Exportación:**
  - Panel HUD con resultados físicos en tiempo real ($x, \Delta x, d, v, a$).
  - Tabla de datos discreta segundo a segundo.
  - **Botón de exportación a archivo `.CSV`** para análisis en Excel.
- **🎯 Modo Desafíos Gamificados (Para el Stand del LibroFest):**
  - 3 niveles interactivos de dificultad progresiva con cálculo de tolerancias, puntuación, efectos de sonido (Web Audio API) y resolución matemática paso a paso.
- **📱 Código QR Integrado:**
  - Generador de QR directo para que cualquier visitante o docente abra el simulador en su smartphone en segundos.
- **💻 Sección Pedagógica de Computación:**
  - Explicación de *Game Loops* (`position += velocity * dt`), interpolación lineal (*Lerp*), odometría robótica y latencia de redes.
