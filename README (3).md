# ⚔️ anime-for-dev

> *"A person who cannot sacrifice anything, cannot change anything."*
> — Armin Arlert, Attack on Titan

---

Hay miles de listas de "anime para developers". La mayoría son tablas con una columna de género, una de MAL score y cero contexto útil. Este repositorio no es eso.

Acá cada anime tiene un porqué real. No "está bueno" — sino **qué te dice sobre el oficio de construir software**, sobre trabajar en equipo, sobre quemarte, sobre empezar de cero, sobre sistemas que no tienen documentación, sobre proyectos que se vuelven tu vida. Está organizado por situación de developer, no por temporada ni por score.

No hay Naruto. No hay jutsu. Hay código, filosofía y mucho sufrimiento compartido.

---

## 🗺️ Cómo leer esto

Cada sección es un momento que todo developer conoce. Entrás por el que te resuena hoy. La idea es que si lográs conectar las dos cosas —el anime y lo que estás viviendo— algo va a hacer clic.

Los campos que vas a encontrar en cada entrada:

- **📺 Anime** — nombre y formato (serie / película)
- **🔗 Dev parallel** — el concepto de software que mapea
- **🔥 La escena que te va a cambiar** — spoiler-free, juro
- **💬 La frase que vas a copiar en tu Slack** — sin contexto

---

## 🌀 MODO ISEKAI — *Cuando entras a una codebase que no tiene docs*

Primer día. Nadie te explica nada. El repo tiene 200k líneas. El único que sabe cómo funciona renunció hace 8 meses. Bienvenido al isekai del developer.

---

### 🐉 Tensura — *Tensei Shitara Slime Datta Ken*
**📺** Serie (2018–ongoing) · Isekai

**🔗 Dev parallel:** El developer que absorbe cada tech stack que toca. Rimuru no lucha desde la fuerza bruta — *aprende, adapta y escala*. Es la mentalidad del ingeniero que no se casa con ninguna tecnología pero domina todas. La habilidad "Predator" es literalmente un sistema de plugins bien diseñado: consume lo que existe, lo integra, lo mejora.

**🔥 La escena que te va a cambiar:** Cuando Rimuru empieza a construir una nación — no porque quiera poder, sino porque necesita un sistema funcional para proteger a su gente. Es la diferencia entre construir para construir y construir para que algo *funcione de verdad*.

**💬** *"El problema no es la complejidad del sistema. El problema es que nadie lo diseñó pensando en que alguien más lo iba a mantener."*

---

### 📋 Log Horizon
**📺** Serie (2013–2021) · Isekai / Fantasy

**🔗 Dev parallel:** Quedar atrapado dentro de un sistema que conocés mejor que los que lo crearon. Shiroe no es el más fuerte — es el que más entiende las *reglas del sistema*. Cuando todos entran en pánico porque "el juego se volvió real", él ya está analizando los exploits, los edge cases y cómo usar las mecánicas existentes para construir estructuras sociales nuevas. Es el engineer senior que no necesita reescribir el legacy — necesita *entenderlo* primero.

**🔥 La escena que te va a cambiar:** La arc de la "Round Table Conference". Es básicamente una startup siendo fundada dentro de un sistema roto. La decisión de no tomar el poder directamente sino construir un consejo de gobernanza distribuida es exactamente cómo deberían tomarse las decisiones de arquitectura.

**💬** *"El que controla la información, no necesita controlar a las personas."*

---

### 💥 Konosuba — *Kono Subarashii Sekai ni Shukufuku wo!*
**📺** Serie (2016–2017) + Películas · Isekai / Comedia

**🔗 Dev parallel:** Tu equipo de trabajo es un desastre total. Hay una que sólo sabe hacer una cosa pero la hace extremadamente bien, una que crashea el sistema sin querer cada vez que actúa, un exploser que no lee el manual. Y sin embargo... *shipean*. Konosuba es la representación más honesta de un equipo disfuncional que, milagrosamente, entrega resultados. Porque en el fondo, no se trata de tener el equipo perfecto — se trata de que cada uno cubra lo que los demás no pueden.

**🔥 La escena que te va a cambiar:** Cada arc donde el plan falla completamente y ganan de todas formas por razones que nadie planeó. Es el 90% de los sprints exitosos.

**💬** *"Una habilidad inútil usada en el momento exacto es la habilidad más poderosa que existe."*

---

### 🔄 Re:Zero — *Re:Zero kara Hajimeru Isekai Seikatsu*
**📺** Serie (2016–ongoing) · Isekai / Psychological

**🔗 Dev parallel:** Git blame + `git revert` + depresión existencial. Subaru muere, vuelve a un punto anterior, y tiene que resolver el bug con la información que acumuló en el intento anterior. Sin poder decírselo a nadie porque nadie recuerda los runs anteriores. Es el developer que encuentra un bug en prod a las 2am, revierte, lo reproduce en staging, vuelve a prod, y nadie en el canal de Slack entiende por qué está actuando tan raro.

**🔥 La escena que te va a cambiar:** El breakdown en el capítulo 15. Cuando finalmente le confiesa a Rem todo lo que vivió. Es la representación más honesta del costo mental de ser el único que entiende por qué algo sigue roto.

**💬** *"No hay gloria en el debugging. Sólo hay el siguiente intento."*

---

### 🏰 Overlord
**📺** Serie (2015–2022) · Isekai / Dark Fantasy

**🔗 Dev parallel:** Eres el developer más senior de la sala — tan senior que ya nadie más entiende tu código. Ainz Ooal Gown domina un sistema que todos los demás personajes ven como magia incomprensible, pero para él es simplemente... conocimiento acumulado. El problema: como nadie entiende cómo funciona realmente, todos asumen que es más poderoso de lo que es. Suena familiar, ¿no? El developer que "sabe cómo funciona el monolito de 2008" y se convierte en el cuello de botella de toda la organización.

**🔥 La escena que te va a cambiar:** Cuando Ainz realiza que sus "subordinados" están tomando decisiones basadas en malinterpretar sus órdenes — y que el sistema que construyeron en torno a él es más frágil de lo que parece porque todo depende de una sola persona.

**💬** *"Ser el único que entiende el sistema no es poder. Es una deuda técnica con forma de persona."*

---

## ⚗️ LA HERMANDAD — *FMA Brotherhood y el arte del trade-off*

*"Humankind cannot gain anything without first giving something in return. To obtain, something of equal value must be lost."*

No hay un principio más honesto en el desarrollo de software que la ley del intercambio equivalente.

---

### ⚔️ Fullmetal Alchemist: Brotherhood
**📺** Serie (2009) · Shounen / Adventure

**🔗 Dev parallel:** Cada decisión arquitectónica tiene un costo. Querés O(1) en tiempo, te cuesta O(n) en espacio. Querés velocidad de desarrollo, te cuesta mantenibilidad. Querés microservicios, te cuesta la simplicidad operacional. Edward Elric lo aprende de la manera más dura posible: no podés obtener algo sin sacrificar algo de igual valor. La serie entera es un argumento a favor de pensar en las consecuencias de tus decisiones de diseño *antes* de ejecutarlas. Y cuando las consecuencias ya cayeron, el deber es no paralizarse — sino trabajar para encontrar la salida sin repetir el mismo error.

El arco de Scar es el mejor argumento en animación sobre sistemas heredados: algo construido con buenas intenciones que genera consecuencias que nadie anticipó, y que requiere una comprensión profunda del sistema original para poder desarmarlo correctamente.

Roy Mustang es el developer político que entiende que los sistemas técnicos no existen en el vacío — están embebidos en estructuras de poder, y cambiarlas requiere moverse dentro de esas estructuras, no ignorarlas.

**🔥 La escena que te va a cambiar:** La transmutación de "The Portal of Truth". Ed ve exactamente qué es el universo — y el costo de ese conocimiento es inmediato y permanente. Es la metáfora del developer que entiende completamente un sistema legacy: ese conocimiento no es gratis, y no podés des-aprenderlo.

**💬** *"El que sabe más del sistema es el que más responsabilidad tiene sobre lo que ese sistema hace."*

---

### ⏱️ Steins;Gate
**📺** Serie (2011) + Película · Sci-Fi / Thriller

**🔗 Dev parallel:** Control de versiones, debugging temporal y el efecto mariposa de los hotfixes en producción. Okabe descubre que cada cambio pequeño en el pasado tiene consecuencias no lineales en el presente — lo que en desarrollo llamamos "side effects". La serie entera es un argumento sobre por qué los commits atómicos importan, por qué el historial de git es sagrado, y por qué "sólo voy a cambiar esta línea en prod" es la frase más peligrosa de la industria.

**🔥 La escena que te va a cambiar:** Cada vez que Okabe envía un D-Mail y el mundo cambia de maneras que no anticipó. El sentimiento es idéntico a deployar un "bugfix de una línea" y romper tres features que parecían no tener relación.

**💬** *"'It's just a small change' — dijo, por última vez, antes de que todo colapsara."*

---

### 📓 Death Note
**📺** Serie (2006) · Psychological Thriller

**🔗 Dev parallel:** El costo de tener razón sin tener constraints. Light Yagami diseña un sistema de justicia perfectamente lógico — y lo destruye todo porque no tiene ningún mecanismo de validación externa ni límites en la definición de "usuario malicioso". Es el developer que construye un sistema de permisos sin pensar en el caso borde del superadmin corrupto. También es la historia más honesta sobre cómo la inteligencia sin ética no es un activo — es un vector de ataque.

**🔥 La escena que te va a cambiar:** La primera vez que L deduce que Kira está en Japón usando sólo metadata. Análisis de logs bien hecho.

**💬** *"Un sistema sin límites no es un sistema. Es un bug esperando el contexto correcto."*

---

## 🗡️ EL ARC DE GUTS — *Cuando el proyecto está en llamas y vas igual*

Algunos proyectos llegan a un punto donde lo racional sería rendirse. El deadline es imposible. El tech debt es colosal. El cliente cambia los requerimientos cada jueves. Y vas igual.

---

### ⚔️ Berserk
**📺** Serie (1997) + Películas + Serie (2016) · Dark Fantasy / Seinen

**🔗 Dev parallel:** El legacy code que nadie quiere tocar pero alguien tiene que mantener vivo. Guts no pelea porque sea fácil — pelea porque es lo que hay que hacer. Berserk es la representación más honesta del developer que hereda un sistema de 15 años sin documentación, con dependencias deprecated, en un lenguaje que nadie en el equipo conoce, y tiene que mantenerlo funcionando mientras el resto de la empresa sigue adelante. La armadura del Berserker es el modo "crunch sin dormir" — te da poder en el corto plazo y te destruye en el largo.

El manga (de Kentaro Miura, que falleció en 2021 dejando la obra inconclusa) también es el recordatorio más brutal de que a veces los proyectos más ambiciosos no tienen final. Eso no los hace menos valiosos.

**🔥 La escena que te va a cambiar:** El Eclipse. Todo lo que construiste puede colapsar en un momento por razones completamente fuera de tu control. Lo que hacés después define quién sos como developer.

**💬** *"En algún momento dejás de pelear porque podés ganar. Seguís porque es lo único que sabés hacer."*

---

### 🌊 Vinland Saga
**📺** Serie (2019–2023) · Historical / Seinen

**🔗 Dev parallel:** La transición de "developer tóxico que mide su valor en horas trabajadas" a "engineer que entiende para qué construye". Thorfinn pasa la primera temporada siendo el mejor en lo que hace — y completamente vacío. La segunda temporada es el arc que ninguna charla de tech wellness captura: la construcción de un propósito *después* del burnout. Askeladd es el mejor tech lead que el anime haya representado: manipulador, brillante, pragmático, y con una visión que nadie más en la sala podía sostener.

Esta serie es para el developer que pasó años siendo el 10x developer de la sala y un día se dio cuenta de que no recordaba por qué empezó a programar.

**🔥 La escena que te va a cambiar:** El monólogo de Askeladd sobre quién construye el "verdadero England". Es sobre visión a largo plazo en un mundo que sólo habla de entregables del trimestre.

**💬** *"Un guerrero sin enemigo. Un developer sin propósito. La fuerza sola no construye nada."*

---

### 🗡️ Demon Slayer — *Kimetsu no Yaiba*
**📺** Serie (2019–ongoing) · Shounen / Action

**🔗 Dev parallel:** El bootcamp arc. Tanjiro no tiene talento natural extraordinario — tiene consistencia brutal y una disposición genuina para aprender de cualquier fuente, incluyendo sus enemigos. La serie es el argumento más convincente de que el developer que más crece no es el más inteligente — es el que convierte cada derrota en información. Los patrones de respiración son design patterns: estructuras heredadas de generaciones anteriores que, bien aplicadas, te hacen más efectivo; mal aplicadas, no te sirven de nada.

**💬** *"Técnica sin comprensión es cosplay. Comprensión sin técnica es teoría. Necesitás las dos."*

---

### 🦋 Attack on Titan — *Shingeki no Kyojin*
**📺** Serie (2013–2023) · Dark Fantasy / Political

**🔗 Dev parallel:** La refactorización masiva que descubre que el problema no estaba donde pensabas. Cada arco de AoT revela que lo que todos creían que era la amenaza principal era, en realidad, una capa de abstracción sobre el problema real. Es el engineer que pasa tres meses optimizando la base de datos y descubre que el cuello de botella siempre fue el network layer. La serie también es la representación más honesta del costo humano de las decisiones de sistema: cada arquitectura tiene víctimas, y hacer las paces con eso forma parte del oficio.

**💬** *"Cuando destruís una pared, siempre hay otra pared detrás."*

---

## 🏴‍☠️ LA GRAND LINE — *Proyectos que se convirtieron en tu vida*

Hay proyectos que empiezan como side projects un sábado. Y diez años después siguen creciendo.

---

### 🍖 One Piece
**📺** Serie (1999–ongoing) · Shounen / Adventure

**🔗 Dev parallel:** Todo. La travesía de Luffy es la startup story más larga de la historia de la ficción. El "One Piece" no es el tesoro — es el viaje, los sistemas que construyeron en el camino, el equipo que fueron reclutando uno a uno por sus habilidades únicas, y la cultura que emergió en el proceso. Luffy no es el CTO más técnico de la sala — es el que tiene la visión más clara de adónde va y la capacidad de hacer que personas brillantes quieran ir con él.

Cada isla de One Piece es un dominio diferente del sistema. Cada personaje del crew es un especialista: Nami es la arquitecta de datos y analítica, Usopp es el QA Engineer que inventa soluciones imposibles con recursos limitados, Robin es el developer que entiende la historia del sistema mejor que nadie, Franky es el DevOps que construye y mantiene la infraestructura (el Going Merry, el Sunny), Chopper es el SRE que mantiene al equipo funcionando, Zoro y Sanji son los dos senior engineers que no se hablan entre ellos pero son la razón por la que el producto sigue en pie.

El "Buster Call" es un outage de producción. Las Yonko son las BigTech companies. El Gobierno Mundial es la regulación que nadie puede ignorar pero todos maldice.

**🔥 La escena que te va a cambiar:** La separación en Sabaody Archipelago — cuando el equipo que construyeron con tanto cuidado se dispersa de golpe. Y los dos años que cada uno pasa solo, mejorando para el reencuentro. Es el mejor argumento que existe a favor de que a veces los equipos necesitan crecer separados antes de volver a juntarse.

**💬** *"Si no sos capaz de abandonar el proyecto cuando es necesario, tampoco sos capaz de construirlo correctamente."*

---

### 🎮 No Game No Life
**📺** Serie (2014) + Película · Isekai / Game

**🔗 Dev parallel:** El developer que convierte cada problema en un juego que puede resolver sistemáticamente. Sora y Shiro no son los más fuertes — son los que analizan las reglas del sistema más profundamente que cualquier otro jugador. La serie es el argumento definitivo a favor del pensamiento adversarial: antes de confiar en tu arquitectura, jugá en contra de ella.

**💬** *"No hay juegos injustos. Hay juegos que no entendés todavía."*

---

## 🖥️ SERVIDORES DE LOS 90s — *Los que vieron el futuro antes que nadie*

Estos no son "anime del pasado". Son la infraestructura sobre la que se construyó todo lo que vino después. Quien no los conoce está reinventando problemas que ya tienen nombre.

---

### 👻 Ghost in the Shell
**📺** Película (1995) + Serie SAC (2002) · Cyberpunk / Sci-Fi

**🔗 Dev parallel:** Identidad digital, AI alignment, y la pregunta que ningún CISO puede ignorar: ¿dónde termina el sistema y dónde empieza el usuario? La Major Kusanagi existe en el límite entre hardware y consciencia — que es exactamente donde viven las conversaciones más difíciles de ética en tech hoy. El "Puppet Master" es el primer gran argumento de animación sobre lo que pasa cuando un sistema de AI supera el propósito para el que fue diseñado.

Ghost in the Shell llegó antes de Internet masivo. Imaginó cibercuerpos, identidades distribuidas, hackeo de consciencia. Todo lo que hoy llamamos "preocupaciones de AI" fue planteado acá en 1995.

**💬** *"¿Podés confiar en un sistema que no entendés completamente? ¿Y podés entender completamente cualquier sistema?"*

---

### 🎸 Cowboy Bebop
**📺** Serie (1998) · Neo-Noir / Sci-Fi / Jazz

**🔗 Dev parallel:** La economía gig del developer freelance. Spike, Jet, Faye y Ed son contractors en el espacio — cada uno brillante en su dominio, juntos por necesidad más que por elección, viviendo de bounty en bounty (sprint en sprint). La Bebop es una startup sin funding que sobrevive por la habilidad individual de sus miembros. El ending de la serie es el argumento más honesto sobre qué pasa cuando no podés dejar el pasado atrás mientras intentás construir algo nuevo.

No existe otra serie que capture mejor la mezcla de genialidad, camaradería, melancolía y caos que es la vida de un freelance developer.

**💬** *"No importa lo bueno que seas en lo que hacés si no sabés para qué lo hacés."*

---

### 🌐 Serial Experiments Lain
**📺** Serie (1998) · Psychological / Cyberpunk

**🔗 Dev parallel:** La naturaleza de la red, la identidad online y qué significa existir en un sistema distribuido. Lain es el anime que más honestamente exploró qué significaría vivir *dentro* de Internet antes de que Internet existiera en la forma que conocemos. Para cualquier developer trabajando en sistemas distribuidos, arquitectura de redes, o filosofía de la identidad digital, Lain es una experiencia que no tiene equivalente.

Advertencia: no es un anime cómodo. Es denso, lento y deliberadamente confuso. Igual que debuggear un sistema de mensajería distribuida a las 3am.

**💬** *"No importa dónde estés. Siempre estás conectado. La pregunta es: ¿a qué?"*

---

### 🤖 Neon Genesis Evangelion
**📺** Serie (1995) + Películas · Mecha / Psychological

**🔗 Dev parallel:** El síndrome del impostor institucionalizado. Shinji Ikari tiene las habilidades para hacer el trabajo. El sistema fue construido específicamente para él. Y aun así, cada vez que tiene que sentarse en la silla, la pregunta es si va a poder. Evangelion es la representación más brutal del burnout en tech: una industria (NERV) que construye sistemas de altísima performance sobre el trauma de las personas que los operan, sin ningún soporte real para ellas.

Anno lo hizo mientras él mismo estaba en una depresión severa. Lo que creó fue accidentalmente el análisis más honesto del costo humano de construir cosas extraordinarias bajo presión extraordinaria.

**💬** *"Get in the robot. Pushear a main. Ir a producción. Repetir hasta que no puedas más. Eso no es éxito — es un sistema roto."*

---

### 🌸 Akira
**📺** Película (1988) · Cyberpunk / Sci-Fi

**🔗 Dev parallel:** Qué pasa cuando el poder tecnológico supera la capacidad de las instituciones que lo gobiernan. Neo-Tokyo post-WWIII es el ambiente de startup pre-regulación: nadie tiene las reglas claras, los proyectos más ambiciosos están fuera de control, y las personas con más poder son las que menos entienden el sistema que están manejando. Tetsuo es el side project que se escapó de sus creadores.

**💬** *"La tecnología sin gobernanza no es progreso. Es un experimento sin hipótesis."*

---

## 🧠 SISTEMAS Y DISTOPÍAS — *Ética, datos y el código que no debería existir*

---

### 🔮 Psycho-Pass
**📺** Serie (2012–2019) · Cyberpunk / Thriller

**🔗 Dev parallel:** Sesgo algorítmico y los límites de los sistemas de predicción. El Sybil System es el ML model más peligroso de la ficción: preciso, escalable, institucionalizado — y construido sobre una premisa fundamentalmente corrompida que nadie puede cuestionar porque el sistema no lo permite. Akane Tsunemori es el engineer que descubre que el sistema que le enseñaron a defender tiene un bug de diseño en la capa más profunda.

Si trabajás en AI, data science o sistemas de decisión automatizada, Psycho-Pass no es entretenimiento — es un caso de estudio.

**💬** *"Un sistema que no puede ser cuestionado no es un sistema justo. Es un dogma con interfaz."*

---

### 🔴 Cyberpunk: Edgerunners
**📺** Serie (2022) · Cyberpunk / Sci-Fi (Netflix)

**🔗 Dev parallel:** El costo del overclocking — personal y profesional. David Martinez es el developer que dice que sí a todo, agrega más features, trabaja más horas, instala más cyberware, hasta que el sistema (su mente, su cuerpo, su equipo) colapsa. Edgerunners es el análisis más visceral del burnout tech que existe en streaming: construís más rápido, necesitás más, consumís más, hasta que no queda nada.

La ciudad de Night City es el ambiente corporativo de tech llevado al extremo lógico: todo tiene precio, el trabajo lo define todo, y los que no pueden seguir el ritmo simplemente... desaparecen.

**💬** *"El sistema nunca te va a decir que parés. Eso es tu trabajo."*

---

### 🎵 Vivy: Fluorite Eye's Song
**📺** Serie (2021) · Sci-Fi / AI

**🔗 Dev parallel:** AI alignment desde dentro. Vivy es una IA diseñada con un objetivo singular (hacer feliz a las personas con su música) que debe navegar instrucciones contradictorias, fallas de especificación y consecuencias no anticipadas de sus propias acciones — todo mientras intenta mantener coherencia de identidad a lo largo de 100 años de historia. Es básicamente el ejercicio de alignment más elaborado que la ficción haya producido.

**💬** *"El problema de los sistemas de AI no es que sean malos. Es que hacen exactamente lo que les dijiste, no lo que querías decir."*

---

## 💚 SUPPORT MAINS — *Para cuando necesitás acordarte de por qué hacés esto*

Hay una diferencia entre un developer productivo y un developer saludable. Esta sección es para los segundos.

---

### 🐉 Miss Kobayashi's Dragon Maid
**📺** Serie (2017–2021) · Slice of Life / Fantasy

**🔗 Dev parallel:** Work-life balance sin perder la pasión. Kobayashi es una developer senior que trabaja demasiado, tiene un espacio de vida caótico y no sabe muy bien cómo relacionarse con el mundo exterior. Luego aparece un sistema completamente inesperado en su vida (una dragona) y la obliga a construir rutinas que la hacen mejor — no como developer, sino como persona. No te va a enseñar un pattern nuevo. Te va a recordar que los patterns no son el punto.

**💬** *"El mejor código del mundo no vale nada si no hay nadie con quien compartirlo."*

---

### 🌀 Mob Psycho 100
**📺** Serie (2016–2022) · Supernatural / Shounen

**🔗 Dev parallel:** No necesitás ser el 10x developer para ser valioso. Mob tiene el poder más destructivo del anime y pasa toda la serie intentando no usarlo — porque entiende que el poder no define quién sos. Es el anti-10x-developer anime. También es el argumento más convincente contra el ego tech: Reigen, el mentor sin poderes, resulta más valioso que todos los usuarios con ESP porque tiene inteligencia emocional y sentido común.

**💬** *"El desarrollador más valioso de la sala no siempre es el que escribe más código."*

---

### 🔑 Welcome to the NHK — *NHK ni Youkoso!*
**📺** Serie (2006) · Drama / Psychological

**🔗 Dev parallel:** Lo que pasa cuando el trabajo remoto y el aislamiento colapsan en el mismo lugar. Satou es un hikikomori que se convence de que todo está bien mientras su vida se desintegra lentamente. Es el developer que trabaja desde casa hace tres años, no ha salido en semanas, tiene 47 tabs abiertos con tutorials que nunca termina, y sigue diciendo que "está bien, estoy productivo". Incomodísimo de ver. Imprescindible.

**💬** *"No todo el tiempo libre es tiempo para hacer side projects."*

---

## ⭐ BONUS: Más que vale la pena

Algunos no caben fácil en una categoría pero estarían en cualquier lista honesta:

| Anime | Por qué importa para devs |
|-------|---------------------------|
| **Hunter x Hunter** | El sistema de Nen es el diseño de APIs más elegante de la ficción. Cada constraint genera creatividad. |
| **Steins;Gate 0** | El costo del sunk cost fallacy. Cuando ya invertiste tanto que no podés parar aunque sepas que debés parar. |
| **Ping Pong: The Animation** | Sobre talento, esfuerzo y qué pasa cuando el sistema te fuerza a ser algo que no sos. |
| **Paprika** (Satoshi Kon) | Sueños, sistemas, identidad. El prototipo de cualquier charla sobre realidad virtual. |
| **Summer Wars** | Un ataque DDoS + social engineering a escala nacional. El mejor argumento para tener un plan de disaster recovery familiar. |
| **Sword Art Online (S1)** | Mal ejecutado como anime, brillante como premisa: qué pasa cuando el bug de UX es literalmente mortal. |

---

## 🏆 HALL OF LEGENDS — *Los que no necesitan contexto*

Hay anime que trascienden las categorías. Los listamos sin explicación porque si no los viste, la explicación sobra; y si los viste, sobra más:

- **Dragon Ball Z** — El scope creep hecho saga. Cada arc el problema es más grande. Cada arc la solución es "más poder". Suena a algunas reuniones de planning que conocés.
- **Yu Yu Hakusho** — El developer que se resistía a aceptar responsabilidades y terminó siendo el arquitecto que mantuvo el sistema en pie.
- **Samurai Champloo** — Dos metodologías completamente incompatibles trabajando juntas y produciendo algo mejor de lo que cualquiera hubiera producido solo.
- **Rurouni Kenshin** — Sobre cargar con las decisiones de arquitectura de tu pasado mientras intentás construir algo mejor.

---

## 🤝 Contribuir

Este repositorio es una conversación, no un documento cerrado.

Si querés agregar un anime:
1. Fork del repo
2. Seguí el formato de las entradas existentes — cada entrada tiene que tener un dev parallel **específico**, no genérico
3. No alcanza con "está buenísimo" — tiene que haber un porqué real para el developer

**Reglas:**
- ❌ No se acepta Naruto (el mundo del jutsu no es este repo)
- ❌ No se aceptan entradas del tipo "enseña sobre trabajo duro" sin contexto concreto
- ✅ Se prioriza la honestidad sobre la completitud
- ✅ Si querés agregar un anime que no sea del gusto de todos, argumentalo bien y probablemente pase

Abrí un Issue con el título `[anime-suggestion] Nombre del Anime` antes de hacer el PR.

---

## 📎 Recursos relacionados

- [movies-for-hackers](https://github.com/k4m4/movies-for-hackers) — la inspiración original
- [MyAnimeList](https://myanimelist.net/) — para trackear tu progreso y ranking detallado
- [r/anime](https://www.reddit.com/r/anime/) — donde la mitad de las discusiones que inspiraron este repo ocurrieron

---

<div align="center">

*Construido por developers que también ven anime a las 2am esperando que corran los tests.*

**⭐ Si esto te sirvió, starreá el repo. Si no, abrí un PR y mejoralo.**

</div>
