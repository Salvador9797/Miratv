# Estado de publicación de Mira

**Versión:** 0.3.1  
**Paquete Android:** `app.mira.movies`  
**versionCode:** 4  
**Código validado:** `3b8d0369318823524c11d513bddb7dffb78aece1`

## Verificaciones completadas

La ejecución [GitHub Actions #75](https://github.com/Salvador9797/Mira/actions/runs/42395174826) terminó correctamente el 7 de noviembre de 2026.

- Pruebas unitarias: correctas.
- Validación de 15 endpoints multimedia: correcta.
- APK QA: generada y verificada con identificador separado `app.mira.movies.debug`.
- Prueba instrumental de reproducción Media3 en emulador Android API 28: correcta.
- APK de producción: alineada con `zipalign` y verificada.
- Firma Android v2 y v3: válida.
- Metadatos: `app.mira.movies`, versionCode 4, versionName 0.3.1.
- SHA-256 de la APK firmada: `cea5e1c84d1f7600e03f2d927fd4efa0e9aa864ac01380a2a6de29ece7802cd6`.
- SHA-256 del certificado de firma: `04:29:A1:6F:E1:3C:AD:95:44:EA:B5:FF:E1:6E:FA:2F:BF:72:B8:34:AC:94:93:9C:D7:49:42:54:0D:25:2B:65`.

## Pendiente antes de la distribución pública

- [ ] Instalar la APK firmada en un dispositivo Android físico y probar inicio, catálogo, búsqueda, favoritos y reproducción.
- [ ] Adjuntar la APK verificada a [GitHub Releases](https://github.com/Salvador9797/Miratv/releases).

## Seguridad de la firma

La clave privada y sus contraseñas no se almacenan en este repositorio público ni se entregan a GitHub Actions. La nueva identidad de firma debe conservarse para todas las actualizaciones futuras; una APK firmada con otro certificado no podrá actualizar esta instalación normalmente.

**Estado: APK firmada y verificada; prueba física y publicación en Releases pendientes.**
