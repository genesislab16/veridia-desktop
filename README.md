# Veridia Desktop — v2.1.1

Sistema de gestión de acceso biométrico para Hikvision DS-K1T321MFWX.

## Descarga

[⬇ Descargar instalador (Windows)](https://github.com/genesislab16/veridia-desktop/releases/latest)

## Características

- Control de membresías, pagos y acceso biométrico
- Sincronización automática con dispositivos Hikvision
- Cajas de turno y reportes de cobros
- Autenticación TOTP para operaciones sensibles en Modo Proveedor
- Auto-actualización integrada

## Instalación

1. Descargá el instalador `.exe` desde [Releases](https://github.com/genesislab16/veridia-desktop/releases/latest)
2. Ejecutá el instalador y seguí el asistente
3. Abrí la app, entrá a **Modo Proveedor** y configurá la conexión a la base de datos

## Novedades — v2.1.1 (2026-06-24)

- Fix: cierre correcto de conexiones a base de datos al salir (prevenía EMAXCONNSESSION en Supabase)
- Fix: cobros ahora funcionan cuando hay una caja abierta (status 'draft' vs 'open')
- Fix: rutas `/api/config/public` y `/system/check-updates` disponibles desde el arranque
- Fix: auto-updater apunta a repo público para verificar actualizaciones
- Mejora UX: spinner mientras la app inicializa la DB en vez de badge de error falso

## Versiones anteriores

Historial completo en [CHANGELOG](https://github.com/genesislab16/isapi/blob/main/CHANGELOG.md).
