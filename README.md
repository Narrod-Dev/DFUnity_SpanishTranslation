# DFUnity_SpanishTranslation

Proyecto de traducción al español para _Daggerfall Unity_. Este repositorio contiene la localización de la interfaz, objetos y configuración del sistema.

Este proyecto busca traducir todo el juego para que se pueda disfrutar de la experiencia completa en español. Nace principalmente de mi deseo personal de jugarlo en mi idioma, no de contar con habilidades lingüísticas avanzadas para una traducción perfecta. Por ello, los textos se han generado con ayuda de herramientas automáticas (Google Translate, Google Gemini versión gratuita, etc.) y luego se han revisado manualmente para evitar incoherencias.

**Importante:** Esta es una traducción pura de texto, por lo que las imágenes que contengan texto (como algunos menús del mod DREAM) permanecerán en inglés.

## 🛠 Archivos traducidos

Actualmente, el proyecto cubre los siguientes archivos de la carpeta `/Text`:

- **GameSettings.txt**: Opciones de juego, interfaz, vídeo y accesibilidad.
- **Internal_Strings.csv**: Información interna.
- **Internal_RSC.csv**: Dialogos, nombres y la mayoria de textos del juego.
- **Internal_Locations.csv**: Nombres de lugares por el mapa.
- **Example_MageLight.csv**: Un ejemplo para hacer un hechizo personalizado.
- **Internal_MagicItems.csv**: Nombres de objetos mágicos y adaptaciones por códigos internos.
- **Internal_Factions.csv**: Nombres de los distintos grupos, gremios y templos del juego.
- **Internal_Settings.csv**: Ajustes avanzados del juego al tocar ESC.
- **Internal_Spells.csv**: Nombres de hechizos.
- **Internal_Items.csv**: Nombres de armas, armaduras y materiales (hierro, daédrico, etc.).
- **Internal_Flats.csv**: Nombres de NPCs, ciudadanos y objetos decorativos (Sprites 2D).
- **MainMenu.txt**: Configuración del lanzador inicial y selección de calidad.
- **ModSystem.txt**: Gestión de mods, prioridades y configuración de plugins.
- **DialogShortcuts.txt**: Atajos de teclado para diálogos y menús de interacción.

## 💻 Instalación

1. Localiza la carpeta de instalación de _Daggerfall Unity_.
2. Navega a `DaggerfallUnity_Data/StreamingAssets/Text/`.
3. Reemplaza los archivos existentes con los de este repositorio.

**Compatibilidad con DREAM:** Si usas el mod DREAM, ten en cuenta que algunos menús usan texturas personalizadas con texto incrustado en inglés, por lo que esas partes podrían no traducirse.

## 🚀 Estado del proyecto

- [x] Menu de Daggerfall Unity (MainMenu.txt, ModSystem.txt, GameSettings.txt, DialogShortcuts.txt) - _listo_
- [ ] Historia principal (carpeta `/Master Localization CSV`) - _en proceso_
- [ ] Misiones (carpeta `/Quests`) — _en proceso_
- [ ] Libros (carpeta `/Books`) — _en proceso_

## 📸 Capturas

![Menú principal del juego traducido](screenshots/mainmenu.png)
_Menú principal con las opciones en español._

![Configuración del sistema de mods](screenshots/modsystem.png)
_Gestión de mods traducida._

![Opciones avanzadas del juego](screenshots/gamesettings.png)
_Configuración de juego, vídeo y accesibilidad._

![Nombres de Hechizos Internos](screenshots/Internal_Spells.png)
_Nombres de hechizos_

![Traducción de ajustes avanzados](screenshots/Internal_Settings.png)
_Ajustes avanzados al tocar ESC_

![Nombre de los distintos grupos, gremios y templos del juego](screenshots/Internal_Factions.png)
_Nombre de los distintos grupos, gremios y templos del juego_

## 📜 Licencia

Este proyecto se distribuye bajo la licencia **GNU GPL v3**. Puedes usarlo, modificarlo y compartirlo libremente, siempre que se mantenga esta misma libertad y se atribuya el trabajo original. Esto garantiza que la traducción permanezca abierta para toda la comunidad.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas ayudar a traducir más archivos (misiones, libros, etc.) o mejorar los existentes, abre un _issue_ o envía un _pull request_. Por favor, mantén el mismo enfoque: traducción automática + revisión manual para conservar la coherencia.
