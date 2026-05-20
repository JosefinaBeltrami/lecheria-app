# Lechería de la Solidaridad — Sistema de Stock

## Stack
- Frontend: HTML/CSS/JS vanilla, una sola página (SPA)
- Backend: Supabase (PostgreSQL + Auth)
- URL Supabase: https://cyefgpuegyfwtiekqtpx.supabase.co

## Tablas en Supabase
- `productos` — catálogo con stock y precios
- `transacciones` — todos los movimientos de stock
- `user_roles` — roles de usuario (admin/usuario/lectura)
- `pending_users` — usuarios creados por admin pendientes de primer login
- `historial_precios` — cambios de precio por producto
- `cierres_mensuales` — registro de cierres ejecutados

## Roles
- admin: acceso total + panel de administración
- usuario: registrar movimientos, editar productos, cierres
- lectura: solo ver stock y productos

## Convenciones
- Todo el código está en un solo archivo HTML
- Usar español para UI y comentarios
- Períodos contables: Septiembre → Agosto
