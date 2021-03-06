# Curso de Intro a la creación de Videojuegos.
> Universidad Nacional de Colombia, sede Medellín. 2022-2


- [Contenido del curso](#contenido-del-curso)
- [Talleres](#talleres-semanales)
- [Profesor](#profesor)
- [Recursos](#recursos)

---

## Contenido del curso
- **Clase 1:** Introducción - [Video](https://www.youtube.com/watch?v=5G81ZNHyEjE&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4)
	- Historia de los videojuegos
	- Industria local y global
	- Proceso de desarrollo
	- Game Engines
- **Clase 2:** Intro. al desarrollo en unity - [Video](https://www.youtube.com/watch?v=ngyY3IzKhLw&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=2)
	- Game Engines - Manejo de memoria
	- Intro. a Unity
	- Game Loop y Orden de ejecución.
	- Transform y Movimiento.
- **Clase 3:** Movimiento y Intro. a físicas. - [Video](https://www.youtube.com/watch?v=8xZHyQdBafQ&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=3)
	- Inputs: GetAxis, GetAxisRaw, Mouse position...
	- Transform: Movimiento y Rotación en 2D.
	- FixedUpdate vs Update.
	- Rigidbody y Colliders.
- **Clase 4:** Físicas: Proyectiles, Colisiones y Rays. - [Video](https://www.youtube.com/watch?v=0S3NuoadBkU&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=5)
	- Rigidbody: Dynamic vs Kinematic vs Static.
	- Movimiento con Rigidbody: Dynamic vs Kinematic.
		- MovePosition vs AddForce vs Velocity.
	- Collisiones, detecciones y Layers
		- OnCollision y OnTrigger: Enter, Stay, Exit.
	- Raycast.
	- Prefabs e Instantiate.
- **Clase 5:** Del 2D al 3D. - [Video](https://www.youtube.com/watch?v=57Si6apbVoQ&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=6)
	- Mallas, Materiales y Shaders.
	- Movimiento en 3D (Transform y Físicas).
	- Mouse, Camara y ScreenPointToRay.
	- Raycast 3D vs Planes
- **Clase 6:** Animaciones - [Video](https://www.youtube.com/watch?v=Ckiht5S214Y&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=7)
	- Rigging y Animaciones.
	- Humanoid vs Generic.
	- Animator y Animation.
	- Animator: Parameter y Layers.
	- Blend Tree y Locomotion.
- **Clase 7:** IA basico para NPC - [Video](https://www.youtube.com/watch?v=9rUl9Y-LJuw&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=8)
	- IA para NPC y enemigos.
	- Finite-State Machine y Blend Tree.
	- Path Finding. Algoritmo A* (A star).
	- Unity y NavMesh.
	- Finite-State Machine en Unity.
- **Clase 8:** <u>Asesoria Proyectos</u>. [Video](https://www.youtube.com/watch?v=fiugdNVAhRs&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=9)
	- Sobre Game Manager.
	- Sober Build (generar ejecutables) y Player Settings.
	- Sobre UI y PlayerPrefs.
	- Sobre Pacman, su movimiento y restricciones.
- **Clase 9:** UI (User Interface) [Video](https://www.youtube.com/watch?v=xN5JydVVbMg&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=10)
	- UI y UX.
	- UI en Unity: Canvas
	- Rect Transform y Anchors.
	- Imagenes, Texto, Botones y más.
	- UI vs 2D (Barra de vida como ejemplo).
	- UI desde código.
	- Eventos para comunicar sistemas.
- **Clase 10:** GameManager y Flujo de juego. [Video](https://www.youtube.com/watch?v=ISLIpxPX7t8&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=11)
	- GameManager y comunicación de sistemas.
	- Herencia en un Sistema de vida.
	- Patrones de diseño.
- **Clase 11:** Audio, Polish & VFX. [Video](https://www.youtube.com/watch?v=f_Gg0ver0fw&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=12)
	- Audio.
	- Scriptable Objects.
	- Coroutinas y Tweens.
	- VFX: Particulas, Trails y Shaders.
- **Clase 12:** Invitado: **Cristian Mazo**. [Video](https://www.youtube.com/watch?v=FJlf5u7pgQc&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=13)
	- Profilling y Optimización con DOTS.
- **Clase 13:** Comodin <u>(No hay clase)</u>.
- **Clase 14:** Builds + Desarrollo Mobile. <u>Asesoria Proyectos</u>. [Video](https://www.youtube.com/watch?v=U5bstAPEryA&list=PL-bINtbD4fuPilX5UsATnRpS66ed4fuB4&index=14)
	- Generación de Builds y Publicación
	- Mobile: Intro. al desarrollo e Inputs.
	- Asesoria: Sobre conecciones en Dungeos.
	- Asesoria: Sobre manejo de celdas (Diccionarios).
- **Clase 15:** Networking. <u>Asesoria Proyectos</u>.
- **Clase 16:** Presentación proyectos finales!

## Talleres semanales
- Tarea #1 (Clase #1): Crear cuenta en GitHub y acceso al repositorio.
- [Tarea #2](./Taller/Taller-2#taller-2/) (Clase #3): Hacer su primer Pull Request.
- [Tarea #3](./Taller/Taller-3#taller-3/) (Clase #3): Torreta - Movimiento y rotación con Transform.
- [Reto #1](./Taller/Reto-1#reto-1/) (Clase #4): Torreta - Disparar al Player.
- [Tarea #4](./Taller/Taller-4#taller-4/) (Clase #5): Dash, Salto y Disparo 3D.
- [Tarea #5](./Taller/Taller-5#leer-antes-de-realizar-el-taller/) (Clase #7): IA en enemigos (atacar y patrullar) - Finite State Machine.
- [Reto #2](./Taller/Reto-2#reto-2/) (Clase #13): Sistema de enemigos, Recarga y Drops.

## Profesor
- J. Alejandro Álvarez. juaalvarezme@unal.edu.co

## Recursos
Todos los recursos (diapositivas, assets, trabajos, etc.) los puede encontrar en [Drive](https://drive.google.com/drive/u/3/folders/15jgDYMw0vqBL88seILhfxZcdDW4PUyGf).

- [Guía](https://youtu.be/xh_1Oyn83no) para clonar y entregar los talleres

## Assets
- Several Assets from [Kenney!](https://www.kenney.nl/assets).
- Battle Royale Duo and Party Monster Duo by [Dungeon Mason](https://assetstore.unity.com/publishers/23554).
- Polygon Starter Pack by [Synty Studios](https://assetstore.unity.com/packages/3d/props/polygon-starter-pack-low-poly-3d-art-by-synty-156819).
- Simple Pixel art styled UI by [Jakub Varga](https://assetstore.unity.com/packages/2d/gui/icons/simple-free-pixel-art-styled-ui-pack-165012).

## Disclaimer
Este repositorio se contruye con fines académicos y de enseñanza. 
Todos los recursos usados son de creación propia o de uso gratis