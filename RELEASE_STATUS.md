# Estado de publicación de Mira

**Versión objetivo:** 0.3.1  
**Paquete Android:** `app.mira.movies`  
**versionCode:** 4  
**Código validado:** `3b8d0369318823524c11d513bddb7dffb78aece1`

## Verificaciones completadas

La ejecución [GitHub Actions #75](https://github.com/Salvador9797/Mira/actions/runs/42395174826) terminó correctamente el 7 de noviembre de 2026.

- Pruebas unitarias: correctas.
- Validación de 15 endpoints multimedia: correcta.
- APK QA: generada y verificada con identificador separado `app.mira.movies.debug`.
- APK de producción: compilada como artefacto **sin firmar** y verificados paquete, versión y metadatos.
- Prueba instrumental de reproducción Media3 en emulador Android API 28: correcta.

## Pasos obligatorios antes de publicar

- [ ] Firmar la APK de producción fuera de GitHub con el keystore permanente de Mira.
- [ ] Verificar que el certificado SHA-256 coincide con la huella permanente documentada en el repositorio privado.
- [ ] Comprobar alineación de la APK.
- [ ] Instalar la APK firmada en un dispositivo Android físico y probar inicio, catálogo, búsqueda, favoritos y reproducción.
- [ ] Calcular y añadir el SHA-256 de la APK firmada a las notas de la versión.
- [ ] Publicar la APK verificada en [GitHub Releases](https://github.com/Salvador9797/Miratv/releases).

## Seguridad de la firma

La clave privada y sus contraseñas no se almacenan en este repositorio público ni se entregan a GitHub Actions. Los artefactos QA y los artefactos de producción sin firmar no son versiones oficiales instalables para distribución.

**Estado actual: validación automatizada aprobada; publicación oficial pendiente de firma permanente y prueba física.**
