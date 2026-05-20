# Lechería · Hogar de la Solidaridad

Aplicación web de gestión interna para la lechería del Hogar de la Solidaridad.

## Tecnologías

- HTML/CSS/JS (sin framework, archivo único)
- [Supabase](https://supabase.com) — base de datos y autenticación
- [SheetJS (xlsx)](https://sheetjs.com) — exportación a Excel

## Uso

Abrir `index.html` en el navegador. No requiere servidor ni build step.

Requiere conexión a internet para Supabase y las fuentes de Google Fonts.

## Estructura

```
lecheria-app/
└── index.html   ← toda la app (HTML + CSS + JS)
```

## Roles de usuario

- **Admin** — acceso completo
- **Usuario** — operaciones habituales
- **Lectura** — solo visualización
