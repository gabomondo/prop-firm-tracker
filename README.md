# Prop Firm Tracker

Programa gratuito para Windows para llevar el control de tus cuentas de prop firms (futuros y CFD): evaluaciones, cuentas fondeadas, payouts, reglas, costos y resultado neto, todo en un solo lugar y guardado en tu PC.

**Web oficial, manual y descarga:** https://gabomondo.com/tracker

## Qué incluye
- Dashboard con el estado de todas tus cuentas y el resultado neto.
- Registro de payouts, gastos y reseteos.
- **Importar capturas** (v2.1): cargás de una vez muchas cuentas desde screenshots de tu historial de compras. La lectura se hace en tu PC, con OCR local y gratis, y siempre podés revisar y editar antes de guardar.
- Opción de lectura con Claude (opcional, con tu propia API key de Anthropic). Solo si la activás, la captura se envía a Anthropic para leerla. Si no, no sale nada de tu PC.
- Copias de seguridad automáticas de tus datos.

## Descargas
Los instaladores están en la sección **[Releases](../../releases)**.

| Versión | Archivo |
|---|---|
| 2.1.0 (última) | `TrackerFondeo-Setup-2.1.0.exe` |
| 2.0.0 | `TrackerFondeo-Setup-2.0.0.exe` |

## Instalación
1. Descargá el instalador de la última versión.
2. Ejecutalo. Se instala solo para tu usuario, sin pedir permisos de administrador.
3. Para actualizar, instalá la versión nueva encima: se conservan todos tus datos.

**Requisitos:** Windows 10 u 11.

**Aviso de Windows (SmartScreen):** el instalador todavía no está firmado digitalmente, así que Windows puede mostrar "Windows protegió su PC". Tocá **Más información → Ejecutar de todas formas**. Podés verificar la integridad del archivo con su SHA256, que figura en la web y en las notas de cada release:

```powershell
Get-FileHash .\TrackerFondeo-Setup-2.1.0.exe -Algorithm SHA256
```

## Soporte
Escribime desde https://gabomondo.com o por mis redes: [YouTube](https://youtube.com/@Gabomondo) · [Instagram](https://instagram.com/gabomondo).

---
*Este repositorio solo aloja los instaladores. Prop Firm Tracker no tiene relación con ninguna prop firm.*
