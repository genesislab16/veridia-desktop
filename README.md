# [1.22.0](https://github.com/genesislab16/isapi/compare/electron-v1.21.0...electron-v1.22.0) (2026-06-21)


### Bug Fixes

* 49-bug sweep — transacciones, error handling, N+1, schema drift, silent no-ops ([b29d447](https://github.com/genesislab16/isapi/commit/b29d447f1b33d0a4ccf81e300d1b5b2082562c12))
* cash closings — método de pago efectivo contabilizado como otros + reactivación sin recarga ([92d0faa](https://github.com/genesislab16/isapi/commit/92d0faa59a7a1f2a9069e6dbffa2c248106a681a))
* evitar EMAXCONNSESSION en /config/billing serializando getConfig ([c0dd0a4](https://github.com/genesislab16/isapi/commit/c0dd0a45465761de8e6ecf1285881bf7d736bfb7))
* facturación resiliente y mensaje claro de enforcement desactivado ([3115c8a](https://github.com/genesislab16/isapi/commit/3115c8a7c2bf6f4fcf1ee94f73b543fecc9b4575))
* migration 017 — remediate columnas usuarios faltantes + catch más preciso ([4f749ce](https://github.com/genesislab16/isapi/commit/4f749cecef44a62ed38e6b5afa0a5bb753f1774d))
* **payments:** gate de caja en POST /payments — rechaza cobros sin caja abierta ([33e10c5](https://github.com/genesislab16/isapi/commit/33e10c504384cd86503f798dc4aaf4d175fd934c))
* rediseño de pestaña Conexión en SetupModal ([dc536d2](https://github.com/genesislab16/isapi/commit/dc536d26cf7c0ce4317d7e4250aa52603a280c4c))
* retry EMAXCONNSESSION en billing y plan-usage; reducir pool a max:2 ([a58033f](https://github.com/genesislab16/isapi/commit/a58033f3ba1cef7c3899fa1ab584b18ebc0508c2))
* reuse shared sql pool in /local/status to prevent PgBouncer session exhaustion ([6529368](https://github.com/genesislab16/isapi/commit/6529368ead583fa0930300d681aa0cf9b7d5d71d))


### Features

* base schema migration + fix TOTP gate en ProviderMode + sync UX redesign con paginación ([4f7346e](https://github.com/genesislab16/isapi/commit/4f7346ecd4f8cbc19968503bef31409e4fabe661))
* botón de reset de configuración local en SetupModal ([7f22b11](https://github.com/genesislab16/isapi/commit/7f22b11f745efe184edb09b3df91312e8685e216))
* botón Resetear en pantalla de login para limpiar config local ([c019d2d](https://github.com/genesislab16/isapi/commit/c019d2d5c51978643fa0f45dafce8870d50eb504))
* migración 015 facturación — billing_invoices, generate_billing_invoices() ([fca2811](https://github.com/genesislab16/isapi/commit/fca2811ed0e120f681e927ae94e91407f666e9d7))
* modal UX horizontal + gate de caja en cobros ([13c0cb0](https://github.com/genesislab16/isapi/commit/13c0cb009bfa37f7c9a1bf12f31c696a84cb678a))
* rediseño UX de login con perfiles de cliente, onboarding y Modo Proveedor TOTP ([b934cde](https://github.com/genesislab16/isapi/commit/b934cdec20666e3441a784e33dd198e3484934f0))
* seed data migration + migration status mejorado en ProviderMode ([a7e203d](https://github.com/genesislab16/isapi/commit/a7e203d492078d62bb0f2e2f5157c3e87767c481))
* TOTP 2FA para operaciones sensibles y límites de plan en UI ([3861e26](https://github.com/genesislab16/isapi/commit/3861e268479b26d42dea02e5bc353a677df20e63))
* v1.21.0 — rediseño UX dispositivos, POS pagos, login, facturación admin ([2a95a22](https://github.com/genesislab16/isapi/commit/2a95a22cf0a07cc700e53d7fe98bc54a6c460950))




