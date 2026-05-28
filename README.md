## (Nombre del proyecto)

El lienzo de Julia



# 1 Datos 



**Titulo** : El lienzo de Julia

**Web:**   (url github.io)

**Autor:**  Julia Crespí Sanz 

 [Profile Card](cmi-card.html)  [Alternate Profile Card](cmi-card2.html)

**Resumen** : Este proyecto pretende crear un recorrido visual por algunas de mis obras y que el personaje pueda interactuar con ellas.

**Estilo/género:**  Portfolio.

**Logotipo** : <img width="67" height="100" alt="IMG_0474" src="https://github.com/user-attachments/assets/c84f6293-ae74-4ad4-a2e5-4aa26d5d60cc" />

**Resolución:** 1200x800px responsivo/o tamaño fijo 

**Probado en:**   MS Edge

**Tamaño proyecto:** 123MB 

**Licencia** Este proyecto tiene una Licencia CC Reconocimiento Compartir igual (CC BY-SA)

**Fecha** : 28/05/2026

**Medios** (donde se tiene presencia relacionada):

- Github:

# 2. Memoria del proyecto 

### 2.1 Storyboard: 



(narra brevemente lo que sucede en tu proyecto, puedes usar 3-4 imágenes de apoyo)



### 2.2. Esquema de navegación 



(imagen con las distintas pantallas de navegación, usa draw.io o cualquier programa de dibujo)







# 3. Metodología

Metodología de desarrollo de productos multimedia basado en una metodología de UX (User Experience)



## Etapa 1: Ideación de proyecto

**Investigación de campo** (propuestas inspiradoras para el proyecto)

- Portfolio [Leonardi Web page](http://www.rleonardi.com/interactive-resume/) para idear cómo organizar el material
- Portfolio interactivo de Lesu en itch.io: lesu.itch.io/interactive-portfolio — portfolio navegable hecho en Godot donde el usuario controla un personaje por un espacio 2D para descubrir el contenido, muy similar en concepto al de este proyecto.
-Portfolio de xolatgames en Godot: gamejolt.com/games/godot-portfolio/916817 — ejemplo de portfolio profesional desarrollado íntegramente en Godot Engine como demostración de habilidades técnicas y creativas.


**Motivación de la propuesta** 

Este proyecto es interesante porque rompe con el formato tradicional del portfolio estático. En lugar de una web o un PDF, el trabajo artístico se presenta dentro de un videojuego 2D navegable, lo que convierte la experiencia de ver las obras en algo activo e inmersivo. 



**Publico / audiencia**

- Orientado a profesores, evaluadores académicos y posibles empleadores del sector artístico y del diseño que quieran conocer mi trabajo y perfil  de una forma diferente.





## Etapa 2: Desarrollo / actividades realizadas

(qué soluciones has planteado y cómo se han resuelto: juego, galería de fotos, grabación de video, etc.)

- Juego: el usuario controla un personaje pixel art (Frisk) que recorre diferentes salas temáticas: pintura, dibujo, escultura y carrusel de imágenes
- Video: el personaje principal entra en escena por la izquierdaa, de fondo se ve un campo y el cielo. Al llegar al centro de la pantalla el personaje agarra un pincel. Arte realizado con pixel art.
- Instrucciones y ayuda al usuario: elementos visuales que guían al jugador por el espacio.
- Menús y elementos de navegación (botones): menú principal, menú de pausa accesible con Esc desde cualquier escena, menú de créditos y botones de navegación entre escenas con transiciones animadas.
- Música de fondo: ambientación sonora diferenciada según la escena.



## Etapa 3: Problemas identificados

-El menú de pausa en la escena principal (main.tscn) aparece por detrás de las obras al estar instanciado dentro de un nodo Area2D con escala reducida, en lugar de en un CanvasLayer.
-El botón de acceso a la escena del personaje presentó dificultades de conexión al estar dentro de un ButtonManager que gestiona los botones de forma especial, lo que impedía conectar señales de la forma habitual.
-El carrusel de imágenes no volvía al inicio al llegar al último elemento, debido a que el sistema de scroll por píxeles y el sistema por índice coexistían sin sincronización, y a que get_child_count() incluía nodos no imagen.



# 4. Conclusiones 

Este proyecto ha supuesto un reto para mí porque soy bastante negada con la tecnología y nunca había hecho nada de programación. Me ha costado muchas horas entender el funcionamiento del programa pero estoy contenta de haber aprendido, ya que es un ámbito que pensaba que nunca iba a llegar a trabajar.

Como mejoras futuras me gustaría pulir el menú de pausa para que funcione de forma consistente en todas las escenas, añadir más animaciones de transición entre salas, incorporar sonidos de pasos al personaje y seguir ampliando el portfolio con nuevas obras a medida que avance en el Grado en Bellas Artes.





# 5 Referencias 

**Artículos y blogs** 

-Trigo, A. (2024). How to Make Your Game Design Portfolio. Alvaro Trigo's Blog. Recuperado de: https://alvarotrigo.com/blog/game-design-portfolios/
-ESDIP Escuela de Arte (2026). Portfolio y reel para videojuegos: cómo hacerlos impactantes. Recuperado de: https://www.esdip.com/blog-escuela-de-arte/portfolio-y-reel-para-videojuegos-como-hacerlos-impactantes/
-Fernández, P. P. (2019). Producción Visual en Videojuegos. Parte IV. Medium. Recuperado de: https://medium.com/@vancorso/producción-visual-en-videojuegos-parte-iv-d21f319fc02f

**Recursos y materiales audiovisuales:**

* Musica:  game-menu_remixed.mp3 y main_menu.mp3 (incluidas en el proyecto)
* Imágenes:  <img width="4365" height="3005" alt="IMG_9981" src="https://github.com/user-attachments/assets/964eeeed-7ed6-4c41-9bf2-6adf450c371c" />
<img width="3209" height="4592" alt="IMG_0497" src="https://github.com/user-attachments/assets/906559bd-9fb9-40db-a5c9-99a3e889cc51" />
<img width="3337" height="4697" alt="IMG_0533" src="https://github.com/user-attachments/assets/e67ddc31-331b-481d-b48b-f7684abdee1f" />
<img width="3365" height="4782" alt="IMG_0483" src="https://github.com/user-attachments/assets/38f0fd7c-a0e6-4687-8a71-b0674bb0f443" />
<img width="3120" height="4468" alt="IMG_8790 (1)" src="https://github.com/user-attachments/assets/247c9b13-dde3-4aa3-b516-24da420f3fbf" />
<img width="3269" height="4659" alt="IMG_5603" src="https://github.com/user-attachments/assets/abdf44a9-8f1a-4a7d-ad7d-0778c412f209" />
<img width="4284" height="5712" alt="IMG_5865" src="https://github.com/user-attachments/assets/aec0b03b-69cd-4519-9024-e039dd04bfab" />
<img width="1097" height="864" alt="IMG_5843" src="https://github.com/user-attachments/assets/9302f12e-25f4-4d02-a95d-7b2b5083bed4" />
<img width="3362" height="4962" alt="IMG_2227" src="https://github.com/user-attachments/assets/b56ad2a9-cb1c-44df-8066-dc962d7eeda5" />
<img width="3492" height="4424" alt="IMG_4937" src="https://github.com/user-attachments/assets/a5b68eae-af84-44f0-84f2-a667dedfc8bd" />
<img width="1344" height="768" alt="IMG_6606" src="https://github.com/user-attachments/assets/31bec321-29f5-4316-8d33-eccf35a819b8" />
<img width="2594" height="3495" alt="IMG_1428" src="https://github.com/user-attachments/assets/5c17f849-df57-4f7d-8cb4-ac6867b0227a" />
<img width="4431" height="3456" alt="IMG_4762" src="https://github.com/user-attachments/assets/081d56b2-4ef4-4af5-8c00-c34e48011bff" />
<img width="2152" height="3049" alt="IMG_0717" src="https://github.com/user-attachments/assets/aaeaeadf-3607-4157-a61b-529eef942a69" />
<img width="3186" height="2737" alt="IMG_1708" src="https://github.com/user-attachments/assets/c3c18dcb-71ac-4656-9a61-acee8c5b8169" />
<img width="4466" height="3345" alt="IMG_2126" src="https://github.com/user-attachments/assets/680a478b-8b99-47e9-8ed2-4bad1cb1eeda" />
<img width="3642" height="3622" alt="IMG_6927" src="https://github.com/user-attachments/assets/7f877c63-e1c1-4f62-8acc-474f2de396c4" />

* Tipografía: Lilita One (LilitaOne-Regular.ttf) · Pixelify Sans (PixelifySans en sus variantes Regular, Medium, SemiBold y Bold) · Limelight (Limelight-Regular.ttf)

**Herramientas utilizadas**

- Godot Engine 4.x
- Aseprite (video animación)

Esta obra está bajo una licencia Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)

<img src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" style="width: 80px">

Mayo 2026
