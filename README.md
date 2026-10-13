# Facturapp – descargas

Aquí se publican las versiones de **Facturapp**, una aplicación de Windows para crear presupuestos, albaranes y facturas.
Este repositorio solo contiene las publicaciones (instalador y notas de cada versión); no incluye código ni datos.

## Instalar

1. Entra en [Releases](../../releases/latest) y descarga `Facturapp-X.Y.Z.msi`.
2. Ejecútalo. Se instala **solo para tu usuario** (no pide permisos de administrador) y no necesitas instalar nada más.
3. Si Windows muestra *"Windows protegió su PC"* (el instalador aún no está firmado), pulsa **Más información › Ejecutar de todas formas**.

Para comprobar la descarga, compara su huella SHA-256 con la del archivo `Facturapp-X.Y.Z.msi.sha256` de la misma versión:

```powershell
(Get-FileHash .\Facturapp-X.Y.Z.msi -Algorithm SHA256).Hash
```

## Actualizar

Facturapp busca versiones nuevas al abrirse. Si hay una, muestra el número de versión y las novedades y pregunta si quieres actualizar.
También puedes buscarla en **Ajustes › Acerca de › Buscar actualizaciones**. Tus datos no se tocan al actualizar.

## Desinstalar

*Configuración de Windows › Aplicaciones › Facturapp › Desinstalar.* Tus espacios de trabajo, clientes y documentos se conservan.
