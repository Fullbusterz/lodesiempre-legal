# Lo de Siempre — páginas legales

Las páginas públicas de la app **Lo de Siempre**, servidas por GitHub Pages:

| | |
|---|---|
| [`index.html`](index.html) | Portada. Existe para que la raíz no sea un 404 |
| [`privacidad.html`](privacidad.html) | Política de privacidad |
| [`borrar-cuenta.html`](borrar-cuenta.html) | Solicitud de borrado de cuenta |

Las dos últimas son **obligatorias** para publicar en Google Play. La de
borrado lo es desde 2023 para cualquier app que permita crear cuenta: tiene
que poder pedirse **sin instalar nada**, porque el caso que Google quiere
cubrir es el de quien ya la desinstaló.

## Por qué este repo existe y es público

El proyecto vive en un repositorio **privado**, y GitHub Pages no sirve desde
repos privados en las cuentas gratuitas. Así que lo único público es esto: tres
páginas que de todas formas tienen que estar a la vista de cualquiera.

El código, el estudio de márgenes y el argumentario de venta se quedan donde
estaban.

## Este repo tiene fecha de caducidad

> **Pendiente, desde el 16-sep-2026.** El único motivo por el que existe es
> esa limitación de GitHub Pages. **Cloudflare Pages sí sirve repos
> privados**, y el dominio `lodesiempre.app` ya está registrado, así que en
> cuanto el sitio se sirva desde el repo del proyecto esta copia sobra.

Y sobra por una razón mejor que ahorrar un repositorio: **mientras haya copia,
hay deriva.** Ya pasó una vez —estas páginas se quedaron con el dorado viejo
`#E0A458` mientras la marca y la app usaban `#EDA92E`, y nadie lo vio hasta
que alguien las comparó fichero a fichero—. Sin copia, ese fallo no existe.

Hay además una razón técnica que obliga: el dominio tiene que servir
`/b/<slug>` para los cartones QR, y eso pide una **reescritura** que GitHub
Pages no sabe hacer. Devolvería 404 en todos los bares.

**El orden para retirarlo**, cuando toque:

1. Cloudflare Pages desplegando `web/` del repo del proyecto.
2. `lodesiempre.app` apuntando ahí, y comprobar las tres páginas más
   `/b/<un-slug-de-verdad>`.
3. Cambiar en Play Console las URL de privacidad y de borrado, si ya estaban
   puestas con la dirección de github.io.
4. Y sólo entonces archivar este repositorio. **Archivar, no borrar**: las
   URL viejas pueden estar en alguna ficha o en algún correo.

Hasta el paso 3, esto sigue siendo lo que se publica, y la regla de abajo
sigue mandando.

## La fuente de verdad NO está aquí

Estos ficheros son una **copia publicada**. El original vive en `web/` del
repositorio del proyecto, junto al código cuyo comportamiento describen: lo que
la política dice sobre el borrado y la anonimización sale de las migraciones
`0001` y `0006`, no de una plantilla.

**Si cambia el comportamiento, se edita allí y se vuelve a copiar aquí.**
Editar sólo esta copia es la forma de que la política acabe mintiendo.

## Lo que estaba pendiente, y ya no

- ~~**El correo `hola@lodesiempre.app` todavía no existe.**~~ **Resuelto el
  16-sep-2026.** La vía de contacto de las dos páginas es ahora
  `lodesiempre.app@gmail.com`, que existe y responde, así que el RGPD queda
  cubierto sin esperar al dominio. Cuando `lodesiempre.app` esté registrado,
  el buzón definitivo será `hola@lodesiempre.app`: se cambia en `web/` del
  repo del proyecto y se vuelve a copiar aquí, **antes** de pegar las URL en
  Play Console y no después.
- ~~Falta el **código postal y la localidad** de la dirección del
  responsable.~~ **Resuelto el 16-sep-2026:** `08970 Sant Joan Despí,
  Barcelona`. La LSSI pide domicilio completo y ya lo está.

Ya no queda ninguno: las dos páginas son publicables. Las cabeceras de cada
fichero llevan la nota de qué se resolvió y cuándo.
