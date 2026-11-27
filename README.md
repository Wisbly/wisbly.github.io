# Sitio personal

La página de inicio enlaza a las secciones del sitio. El juego **Palabra Peligrosa** está disponible en `/palabra-peligrosa/` y Memento Mori en `/memento-mori/`.

Las páginas CV, Cartas, Imágenes y Links son marcadores de posición hasta agregar su contenido.

## Palabra Peligrosa ☠

Juego de fiesta tipo **Tabú / Password** para dos equipos, hecho en un único archivo `index.html`
(HTML + CSS + JavaScript, sin dependencias ni servidores). Pensado para proyectar en la tele y jugar con amigos.

**▶ Jugar online:** https://wisbly.github.io/palabra-peligrosa/

## Cómo se juega
Cada tarjeta tiene una palabra **CORRECTA** (la que tu equipo debe adivinar) y una **PELIGROSA**
(el chilenismo tentador que **no** puedes decir). Si tu compañero adivina la correcta, ganas punto.
Si se te escapa la peligrosa, cae la penalización.

## Características
- 9 categorías y **160 tarjetas** iniciales (editables).
- Equipos con nombres y marcador, turnos automáticos y sin límite de tiempo.
- Modos de victoria y penalización configurables, pases, repeticiones, sonidos y animaciones.
- **Administrador de palabras**: agregar / editar / eliminar / buscar tarjetas desde la propia app.
- Importar / exportar **JSON** y **CSV**, copia de seguridad y restaurar base inicial.
- Guardado automático en el navegador (`localStorage`). Responsive + pantalla completa.

## Uso local
Abre `index.html` para visitar el inicio o `palabra-peligrosa/index.html` para abrir el juego. No necesita instalar nada.

---
Todo (tarjetas, categorías, configuración) se administra desde la interfaz, sin tocar el código.
