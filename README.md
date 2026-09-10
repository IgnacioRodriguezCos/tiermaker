# TierMaker

Aplicación web estática para crear rankings tipo *tier list*, inspirada en [TierMaker](https://tiermaker.com). Construida en un solo archivo HTML sin dependencias ni backend.

## Características

- **Tiers editables** con colores personalizables (S, A, B, C, D, F por defecto)
- **Drag & drop** funcional en desktop y móvil (pointer events)
- **Carga de items desde archivo `.txt`** — cada línea se convierte en un item arrastrable
- **Materias precargadas** — al abrir por primera vez, 49 materias de Ingeniería Informática ya están en "Sin Clasificar"
- **Agregar items individuales** desde la barra superior
- **Agregar, renombrar, reordenar y eliminar tiers** dinámicamente
- **Botón ✕** en items dentro de tiers para devolverlos a "Sin Clasificar"
- **Exportar / Importar** el ranking completo en formato JSON
- **Auto-guardado** en `localStorage` — el estado persiste al recargar
- **Responsive** — funciona en móvil y escritorio

## Uso

1. Abrí `index.html` en cualquier navegador.
2. Arrastrá los items desde "Sin Clasificar" a los tiers que correspondan.
3. Para cargar tus propios items, creá un `.txt` con un item por línea y usá el botón **Cargar TXT**.
4. Exportá tu ranking con **Exportar** para guardarlo como JSON.

## Estructura

```
tiermaker/
├── index.html      # Toda la app (HTML + CSS + JS)
├── Materias.txt    # Lista de materias (49 items)
└── README.md
```

## Tech

- HTML5 + CSS3 + JavaScript vanilla
- Sin frameworks, sin build, sin dependencias

## Licencia

Uso libre.
