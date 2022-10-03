# Homecenter Store
Homecenter Store es un modelo básico de escaparate basado en VTEX IO Store Framework.

La tienda es una copia de la pagina homecenter.com.co

![homecenter](https://user-images.githubusercontent.com/84733911/193512262-b99efc3d-0c8f-4f24-b7e5-84cfa6b70564.png)

## Configuración
### Paso 1 - Configuración básica

Acceda a la [guía de configuración básica](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1) de VTEX IO y siga todos los pasos indicados.

Al final de la configuración, debe tener instalada la interfaz de línea de comandos de VTEX (Toolbelt) junto con un espacio de trabajo de desarrollador en el que puede trabajar.

### Paso 2 - Clonación del repositorio

[Clonar](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) este repositorio en sus archivos locales para poder comenzar a trabajar en él de manera efectiva.

Luego, acceda al directorio del repositorio usando su terminal.

### Paso 3 - Editar el Manifest.json

Una vez en el directorio del repositorio, es hora de editar el archivo `manifest.json` de la plantilla mínima.

Una vez que esté en el archivo, debe reemplazar los valores `vendor` y `name`. `vendor` es el nombre de la cuenta del partner en la que está trabajando y `name` es cualquier nombre que desee para su tema. Por ejemplo:

```json
{
  "vendor": "partner",
  "name": "store--name",
}
```

### Paso 4 - Instalar apps necesarias

Para usar Store Framework y trabajar en el tema de su tienda, es necesario tener instalados `vtex.store-sitemap` y `vtex.store`.

Ejecute `vtex list` y verifique si esas aplicaciones ya están instaladas.

Si no lo están, ejecute el siguiente comando para instalarlos: `vtex install vtex.store-sitemap vtex.store -f`

### Paso 5 - Desinstalar el store-theme predeterminado

Al ejecutar `vtex list`, puede verificar si algún tema está instalado.

Es común tener ya instalado un `vtex.store-theme` cuando inicia el proceso de desarrollo frontal de la tienda.

Por lo tanto, si lo encuentra en la lista de aplicaciones, copie su nombre y version, luego utilícelo junto con el comando `vtex uninstall`. Por ejemplo:

```json
vtex uninstall vtex.store-theme@0.0.1
```

### Paso 6 - Ejecute un preview de la tienda

Entonces ha llegado el momento de cargar todos los cambios que realizó en sus archivos locales a la plataforma. Para eso, use el comando `vtex link`.

Si el proceso se ejecuta sin ningún error, se mostrará el siguiente mensaje: `Aplicación vinculada con éxito`. Luego, ejecute el comando `vtex browser` para abrir una ventana del navegador que tenga su tienda vinculada.

Esto le permitirá ver los cambios aplicados en tiempo real, a través de la cuenta y el espacio de trabajo en el que está trabajando.

## peerDependencies
1. "vtex.reviews-and-ratings"
2. "vtex.wish-list"

## Store Components
1. "vtex.store"
2. "vtex.store-header"
3. "vtex.product-summary"
4. "vtex.store-footer"
5. "vtex.store-components"
6. "vtex.styleguide"
7. "vtex.slider"
8. "vtex.carousel"
9. "vtex.shelf"
10. "vtex.menu"
11. "vtex.minicart"
12. "vtex.product-details"
13. "vtex.product-kit"
14. "vtex.search-result"
15. "vtex.login"
16. "vtex.my-account"
17. "vtex.flex-layout"
18. "vtex.rich-text"
19. "vtex.store-drawer"
20. "vtex.locale-switcher"
21. "vtex.product-quantity"
22. "vtex.product-identifier"
23. "vtex.breadcrumb"
24. "vtex.sticky-layout"
25. "vtex.product-customizer"
26. "vtex.stack-layout"
27. "vtex.product-specification-badges"
28. "vtex.product-review-interfaces"
29. "vtex.telemarketing"
30. "vtex.order-placed"
31. "vtex.checkout-summary"
32. "vtex.product-list"
33. "vtex.add-to-cart-button"
34. "vtex.product-bookmark-interfaces"
35. "vtex.responsive-layout"
36. "vtex.slider-layout"
37. "vtex.store-image"
38. "vtex.store-icons"
39. "vtex.modal-layout"
40. "vtex.store-link"
41. "vtex.product-gifts"
42. "vtex.product-price"
43. "vtex.disclosure-layout"
44. "vtex.store-form"
45. "vtex.product-highlights"
46. "vtex.product-specifications"
47. "vtex.tab-layout"
48. "vtex.condition-layout"
49. "vtex.css-handles"

## Custom Apps (Componentes custom que deben instalarse con la tienda)
1. "itgloberspartnercl.whatsapp-button"
2. "itgloberspartnercl.bullets-diagramation"
3. "itgloberspartnercl.add-to-cart-info"
4. "itgloberspartnercl.custom-department-search"
5. "itgloberspartnercl.pdf-reader"
6. "itgloberspartnercl.quick-order"
7. "itgloberspartnercl.special-diagramation"

## Contributors
1. Ruben Dario Suarez   
