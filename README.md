# 🎒 Mi aventura Pokémon

Un juego de aventura por elecciones, hecho por fans y sin fines de lucro, que se juega directo en el navegador. Vivís la vida de un entrenador desde los **10 hasta los 35 años**, a lo largo de **100 estaciones**, y cada decisión te lleva a un final distinto.

👉 **Jugar:** `https://[tu-usuario].github.io/[nombre-del-repo]/`

## Qué podés hacer

- Elegir tu nombre, tu origen y tu primer Pokémon.
- Explorar zonas, capturar, entrenar y evolucionar a tus Pokémon (151 especies de la primera generación).
- Desafiar los 8 gimnasios y la Liga Pokémon, y enfrentarte a tu rival Blue en momentos clave.
- Seguir otros caminos: coleccionista, Profesor, gimnasio propio o el Equipo Rocket.
- Elegir cómo terminar tu historia entre más de diez finales, con una historia final personalizada.
- Conseguir logros, un puntaje con calificación y un lugar en tu Salón de la Fama.
- Consultar la **Guía y glosario** dentro del juego (botón 📖) para cualquier duda sobre stats, probabilidades, zonas, finales y más.

## Cómo se juega

Cada estación elegís una acción (explorar, entrenar, estudiar, el mercado, gimnasios y más). Algunas traen eventos con opciones: cada una muestra su probabilidad de salir bien, neutral o mal, y qué la modifica. Tus stats, tu equipo, tus objetos y tu reputación cambian esas probabilidades.

## Tus partidas

- Todo se guarda **en tu navegador** (almacenamiento local). No hay cuentas ni servidor.
- Podés tener hasta 5 partidas guardadas a la vez y borrarlas desde la pantalla de inicio.
- Si cambiás de navegador, de dispositivo o borrás los datos del sitio, **no vas a ver tus partidas ni tus logros**.
- Los logros y el Salón de la Fama también viven en tu navegador. El puntaje se puede compartir copiando el resumen que aparece al final de la partida.

## Sonido

- La música ambiental y los efectos **se generan dentro del juego** (Web Audio): no hay archivos de audio ni música con derechos de autor.
- Hay un menú **Opciones** (desde el título o el ícono del engranaje) con una sección de sonido para subir, bajar o silenciar la música y los efectos. La música no empieza hasta que tocás algo en la página (así lo exigen los navegadores).
- Si querés usar tus propios temas **libres de derechos** (por ejemplo, con licencia CC0), subilos al repositorio y poné sus rutas en la constante `MUSIC_FILES` del `index.html`. No incluyas música comercial de terceros.

## Animaciones y efectos
Los Pokémon se ven animados (los sprites animados de Gen 5 del repositorio público PokeAPI/sprites) en la selección de inicial, el panel del equipo, los gimnasios, las capturas, las evoluciones y los finales. **Se cargan desde internet cuando hay conexión**: no van dentro del archivo (los 151 normales y shiny pesarían unos 11 MB). Si no cargan, el juego muestra el sprite quieto que sí viene incluido, y todo funciona igual.

También hay efectos dibujados dentro del juego: destellos y marco especial al capturar (más fuertes con raros y shiny), una pantalla de evolución, la pantalla «VS» en gimnasios, confeti y fuegos artificiales en victorias y finales, y partículas según la estación (pétalos, luciérnagas, hojas, nieve). En «Opciones» podés apagar los sprites animados, elegir cuántos efectos querés (completos, reducidos o apagados) y mover una barra de **partículas de estación**, de 0 a 100%. Si tu dispositivo pide «reducir movimiento», los efectos quedan apagados.

## Privacidad

El juego es un único archivo (`index.html`). No envía datos a ningún servidor, no usa analíticas ni cookies de seguimiento y no carga recursos externos: los sprites vienen incluidos en el archivo y el audio se genera en tu navegador.

## Publicarlo en GitHub Pages

1. Creá un repositorio **público** en GitHub.
2. Subí `index.html` y este `README.md` a la rama principal.
3. En **Settings → Pages**, elegí publicar desde esa rama (carpeta raíz).
4. Esperá un momento y abrí la dirección que te muestra GitHub.

Para actualizar el juego, reemplazá `index.html` por la versión nueva. Elegí bien el nombre del repositorio desde el principio: si cambia la dirección, los jugadores pierden sus partidas guardadas (el navegador las guarda por dirección).

## Aviso legal

Este es un proyecto de fans, **gratuito y sin fines de lucro**. No está afiliado, patrocinado ni respaldado por Nintendo, Game Freak, Creatures ni The Pokémon Company. Pokémon y los nombres de personajes son marcas de sus respectivos dueños.

Los sprites de Pokémon y de objetos incluidos en el archivo provienen del repositorio público [PokeAPI/sprites](https://github.com/PokeAPI/sprites) y pertenecen a sus dueños: Nintendo, Game Freak y The Pokémon Company. Si sos titular de derechos y querés que se retire algún contenido, escribime y lo hago.

## Contacto y errores

Si encontrás un error o tenés una sugerencia, abrí un *issue* en este repositorio o escribí a **[tu contacto]**.

## Créditos

Creado por **[tu nombre]**.

Los sprites de los líderes de gimnasio (pantalla de Medallas) provienen del desensamblado público [pret/pokered](https://github.com/pret/pokered) (`gfx/trainers`), recoloreados, y pertenecen a Nintendo y Game Freak.

Los íconos de los menús (mochila, guía, logros, diario, opciones, sonido, Salón de la Fama y reloj de arena) son de [Phosphor Icons](https://phosphoricons.com), en su estilo duotone, con licencia MIT. El ícono de la Pokédex es propio.
