
# 🎯 Shooter-DSJ

**Shooter-DSJ** es un videojuego desarrollado en Unity, orientado a estudiantes de primaria, con el objetivo de evaluar habilidades espaciales y coordinación visomotora mediante mecánicas de disparo adaptadas. El juego incluye enemigos, armas recogibles, efectos visuales y un sistema de puntuación gestionado por un Game Manager.

---

## 🕹️ Características principales

- Sistema de disparo con proyectiles y colisiones.
- Enemigos con comportamiento y salud (robots, torretas).
- Efectos de explosión al eliminar enemigos.
- Sistema de recogida de munición y armas.
- Escenarios diseñados para navegación y combate básicos.
- Gestión de oleadas y progreso mediante `GameManager`.

---

## 📁 Estructura del proyecto

```plaintext
/Scripts
  ├── Enemies/
  │   ├── EnemyHealth.cs        # Control de salud y destrucción del enemigo
  │   ├── Explosion.cs          # Efectos al destruir enemigos
  │   ├── Projectile.cs         # Lógica de los disparos
  │   ├── Robot.cs              # Comportamiento de enemigos tipo robot
  │   ├── SpawnGate.cs          # Punto de aparición de enemigos
  │   └── Turret.cs             # Lógica de torretas estáticas
  ├── Misc/
  │   └── GameManager.cs        # Control del estado general del juego
  └── Pickups/
      ├── Pickup.cs             # Clase base para objetos recogibles
      ├── AmmoPickup.cs         # Recogida de munición
      └── WeaponPickup.cs       # Recogida de armas
```

---

## 🛠️ Tecnologías utilizadas

- **Motor de juego:** Unity (versión recomendada: 2022.x o superior)
- **Lenguaje:** C# (MonoBehaviour scripts)
- **Gráficos y entorno:** 3D básico con objetos prefabricados y animaciones
- **Sistema de cámara:** Cinemachine (para retroceso y enfoque dinámico)
- **Interfaz de usuario (UI):** Canvas, texto y HUD básico

---

## 📊 Evaluación y propósito

Este juego fue parte de un estudio académico para observar cómo diferentes rangos etarios (3.º, 4.º y 5.º de primaria) interactúan con un entorno 3D con mecánicas de disparo. Se midieron variables como:

- Precisión de disparo  
- Tiempo de resolución de objetivos  
- Número de colisiones  
- Satisfacción del usuario (escala Likert)

---

## 🧩 Posibles mejoras

- Implementar IA más compleja para enemigos  
- Mejorar la retroalimentación visual y sonora  
- Ajustar la dificultad de forma dinámica según el jugador

---

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/iccoscco/Shooter-DSJ.git
   ```
2. Abre el proyecto en Unity.
3. Asegúrate de tener instaladas las dependencias como **Cinemachine** desde el *Package Manager*.
4. Ejecuta la escena principal desde el panel de `Scenes`.

---

## 📄 Licencia

Proyecto desarrollado con fines académicos. El código puede reutilizarse o modificarse con fines no comerciales, citando al autor original.

---

## 🙌 Créditos

Proyecto desarrollado por **Italo Ccoscco Alvis** y **Oliver Mayta Nolasco**.
