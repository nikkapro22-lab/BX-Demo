# BX completo

Descarga BX 0.2.0 para Windows y Mac. Esta entrega incluye la aplicación completa actual y su servidor local, con arranque por doble clic. No requiere instalar Node.js ni tener una cuenta de GitHub.

| Equipo | Instalador |
| --- | --- |
| Windows x64 (Intel/AMD) | [Descargar para Windows](https://github.com/nikkapro22-lab/BX-Demo/releases/download/v0.2.0/BX-0.2.0-win-x64.exe) |
| Mac Apple Silicon (M1 y posteriores) | [Descargar para Mac Apple Silicon](https://github.com/nikkapro22-lab/BX-Demo/releases/download/v0.2.0/BX-0.2.0-mac-arm64.dmg) |
| Mac Intel | [Descargar para Mac Intel](https://github.com/nikkapro22-lab/BX-Demo/releases/download/v0.2.0/BX-0.2.0-mac-x64.dmg) |

[Notas y sumas SHA-256 de la versión](https://github.com/nikkapro22-lab/BX-Demo/releases/tag/v0.2.0).

En Windows, ejecuta el instalador y sigue sus pasos. En Mac, abre el DMG y arrastra **BX** a **Aplicaciones**. Consulta tu procesador en  → Acerca de esta Mac.

Los instaladores no tienen firma comercial de Windows ni notarización de Apple. El sistema operativo puede mostrar advertencias. No se requiere desactivar las protecciones del equipo.

## Alcance de esta entrega

La versión 0.2.0 conserva el código y las rutas actuales de la aplicación. Es distinta de la demo limitada 0.1.0 para estudiantes, que continúa disponible en [versiones anteriores](https://github.com/nikkapro22-lab/BX-Demo/releases/tag/v0.1.0).

El perfil **BX Full** guarda los datos de esta instalación. No importa automáticamente las sesiones, bibliotecas ni cuentas del autor, de la aplicación de desarrollo o de la demo estudiantil. No incluye claves privadas ni datos de empresas.

Las funciones que dependen de modelos locales, Python/transcripción, Astrax/Hermes, infraestructura de reuniones, proveedores de IA, OAuth o servicios empresariales requieren sus propios runtimes, cuentas y configuración en el equipo de destino. Incluir sus interfaces y código no conecta esos servicios automáticamente. Sus controles de autenticación se conservan. Un archivo opcional `bx.env` en el perfil BX Full permite configurar los servicios propios de la instalación.

## Este repositorio

El nombre histórico **BX-Demo** se conserva como canal público de descargas. El código de desarrollo permanece en su repositorio privado. Distribuir los binarios no concede una licencia de código abierto ni permiso para extraer o redistribuir los recursos visuales por separado.

Para reportar un problema, indica sistema operativo, versión y sección visitada en [Issues](https://github.com/nikkapro22-lab/BX-Demo/issues). Los reportes son públicos: evita incluir claves o datos personales.

## Verificación

La instalación y el arranque de [Windows](https://github.com/nikkapro22-lab/BX-Demo/actions/runs/40617625821) y la apertura de [Mac Intel](https://github.com/nikkapro22-lab/BX-Demo/actions/runs/40616066080) pasaron sus pruebas nativas. Mac Apple Silicon pasó la prueba de arranque local con el paquete final. Ambos DMG pasaron `hdiutil verify`; las tres sumas SHA-256 coinciden con los archivos alojados en GitHub.
