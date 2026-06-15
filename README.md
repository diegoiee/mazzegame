# 🐱 El Laberinto del Gatito

Un mini-juego de laberinto en **ASCII**, sin dependencias: todo vive en un solo archivo [`index.html`](index.html).

**👉 Jugar:** https://diegoiee.github.io/mazzegame/

## Cómo se juega

Un gatito se metió en un laberinto y lo seguiste hasta adentro. Ahora tenés que atraparlo y **salir de memoria, contra reloj**.

- **Ida** 🐈 — Ves todo el laberinto. Recorrelo y atrapá al gatito `♥` (aparece en la celda más lejana). Memorizá el camino.
- **Vuelta** 🐱 — Arranca el reloj y cae la **niebla**: solo ves lo que tenés cerca. Volvé a la salida `▒` recordando el camino que hiciste.

### Puntaje
- Salís a tiempo → `segundos_restantes × 10 + nivel × 50` puntos y subís de nivel.
- Se acaba el tiempo → **0 puntos**, reintentás el nivel.
- Cada nivel agranda el laberinto y (desde el nivel 3) reduce la visión en la niebla.

### Controles
- **4 botones en pantalla** (▲ ▼ ◀ ▶), pensados para móvil/touch.
- En compu también funcionan las **flechas** y **WASD**.

### Símbolos
| Símbolo | Significado |
|---|---|
| `@` | vos |
| `♥` | gatito |
| `▒` | salida (= entrada) |
| `#` | pared |
| `·` | rastro reciente |

## Jugar en el iPhone 📱
1. Abrí la URL en **Safari**.
2. Botón **Compartir** → **"Agregar a pantalla de inicio"**.
3. Se abre a pantalla completa como una app, ideal para los botones táctiles.

## Correrlo local
No necesita servidor: abrí `index.html` en cualquier navegador.

---
Hecho con 🐈 y un poco de ASCII.
