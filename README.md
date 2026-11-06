# Puente de impresión para Windows

Paquete local que permite a Telconaudit Business comunicarse con una impresora instalada en Windows para solicitar la apertura del cajón portamonedas.

## Descarga

[Descargar el instalador para Windows](https://github.com/telconaudit/puente_impresion_Windows/raw/refs/heads/Principal/Telconaudit-Cajon-Puente-Windows.zip)

## Contenido e instalación

Descomprime el ZIP. Instala primero la extensión firmada de Firefox o Chrome correspondiente. A continuación, ejecuta `Install-Bridge.ps1` en Windows. Para Chrome, sigue las instrucciones de instalación que acompañan la extensión. Reinicia el navegador y selecciona la impresora de Windows desde la configuración de TPV Hostelería.

Para quitar el puente, ejecuta `Uninstall-Bridge.ps1`.

Este paquete requiere Windows, la extensión del navegador y una impresora instalada y configurada en el sistema. La prueba de apertura debe confirmarse con la impresora y el cajón conectados.

SHA-256 del ZIP: `$hash`
