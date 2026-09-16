# Canarias Accesible Suite Lab v0.3

Versión de laboratorio centrada en fidelidad del módulo técnico.

## Cambio principal
La pestaña Partes ya no recrea ni simplifica los formularios. Incluye la aplicación original `postventa-canarias` dentro de `/tecnicos/`, manteniendo sus pantallas de Instalación, Reparación, Mantenimiento, Historial, cálculos, fotografías y almacenamiento local.

## Cambios mínimos realizados al módulo técnico
- enlace de retorno a la Suite en la pantalla principal;
- service worker v23 para convivir con la caché de la Suite sin borrarla;
- ningún cambio funcional deliberado en los formularios.

## Aún no incluido
Supabase y sincronización central. Primero debe validarse paridad funcional con la app técnica original.
