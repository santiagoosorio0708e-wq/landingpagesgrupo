# Landing Pages Grupo - Réplicas en HTML y CSS

Este repositorio reúne múltiples ejercicios de maquetación web cuyo objetivo es **imitar y replicar páginas solicitadas** usando únicamente tecnologías base del frontend:

- `HTML5` para estructura
- `CSS3` para estilos y layout
- Assets locales (imágenes, íconos y recursos gráficos)

Además, se agregó un **menú principal global** en la raíz del proyecto para navegar por número de página.

---

## Objetivo del proyecto

Construir una colección de landing pages estáticas, cada una aislada por carpeta, para practicar:

- Estructuración semántica de interfaces.
- Maquetación con CSS (posicionamiento, tipografía, espaciado y composición visual).
- Organización de recursos por página.
- Reproducción visual fiel de diseños entregados.

---

## Alcance y proceso realizado

Durante el desarrollo del folder se siguió una lógica de trabajo por entregas/páginas:

1. Se recibe una referencia visual o requerimiento de diseño.
2. Se crea una carpeta identificada por número.
3. Se construye la página en HTML.
4. Se estila con CSS propio de esa carpeta.
5. Se agregan y enlazan recursos multimedia locales.
6. Se valida visualmente la réplica.
7. Se integra al menú raíz para acceso centralizado.

Resultado: una base de varias páginas independientes listas para visualizarse localmente.

---

## Estructura del repositorio

```text
landingpagesgrupo-main/
├── index.html            # Menú principal (selector por número de página)
├── 3/
├── 4/
├── 6/
├── 10/
├── 11/
├── 12/
├── 14/
├── 15/
├── 22/
├── 33/
├── 38/
├── 40/
├── 41/
├── 45/
└── 50/
```

Patrón interno por carpeta:

- Archivo principal (`index.html` o `PaginaXX.html`)
- Carpeta de estilos (`CSS/` o `css/`)
- Carpeta de recursos (`media/` o `images/`)

---

## Menú principal agregado (raíz)

Archivo: `index.html` (en la raíz)

Funcionalidades:

- Permite ingresar un número de página.
- Redirige automáticamente a la carpeta/archivo correspondiente.
- Muestra mensaje de error si el número no existe.
- Incluye accesos rápidos a todas las páginas registradas.

---

## Mapa actual de páginas

| Número | Ruta de acceso |
|---|---|
| 3 | `3/index.html` |
| 4 | `4/index.html` |
| 6 | `6/Pagina6.html` |
| 10 | `10/index.html` |
| 11 | `11/index.html` |
| 12 | `12/index.html` |
| 14 | `14/Pagina14.html` |
| 15 | `15/index.html` |
| 22 | `22/index.html` |
| 33 | `33/Pagina33.html` |
| 38 | `38/Pagina38.html` |
| 40 | `40/Pagina40.html` |
| 41 | `41/index.html` |
| 45 | `45/index.html` |
| 50 | `50/index.html` |

---

## Cómo ejecutar el proyecto

### Opción 1: abrir directamente

Abrir `index.html` (raíz) en el navegador.

### Opción 2: servidor local (recomendado)

Desde la raíz del proyecto:

```bash
python3 -m http.server 5500
```

Luego abrir:

`http://localhost:5500/`

Esto evita problemas de rutas relativas en algunos navegadores.

---

## Convenciones usadas

- Carpetas numeradas para separar cada réplica.
- Estilos y recursos encapsulados por página.
- Nomenclatura mixta heredada (`CSS`/`css`, `media`/`images`, `index.html`/`PaginaXX.html`).

---

## Mantenimiento y ampliación

Para agregar una nueva página:

1. Crear nueva carpeta numérica (ej. `60/`).
2. Agregar su HTML principal y estilos.
3. Guardar assets dentro de la carpeta correspondiente.
4. Registrar la ruta en el objeto `pages` del `index.html` raíz.
5. Probar acceso directo y acceso desde el menú principal.

---

## Estado del proyecto

Proyecto académico/práctico de réplicas visuales en HTML/CSS, organizado para navegación centralizada y crecimiento incremental por páginas.
