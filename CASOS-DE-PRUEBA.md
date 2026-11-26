# Casos de Prueba – SÚPER KOMPRAS

**Aplicación:** https://superkompras.com.mx/

**Tipo de pruebas:** Pruebas funcionales.

**Técnica:** Black Box Testing (Caja Negra).

**Fecha de ejecución:** 26 de noviembre de 2026.

**Resultado general:** 15 PASS.

---

## CP-001 – Acceso a la categoría BEBIDAS

**Precondiciones:** El sitio web se encuentra disponible.

**Pasos:**
1. Ingresar al sitio web de SÚPER KOMPRAS.
2. Localizar la categoría BEBIDAS.
3. Seleccionar la categoría.

**Resultado esperado:** La página de la categoría debe abrir correctamente y mostrar los productos disponibles.

**Resultado obtenido:** La categoría abrió y funcionó correctamente.

**Estado:** PASS.

---

## CP-002 – Acceso a la categoría SALCHICHONERÍA

**Precondiciones:** El sitio web se encuentra disponible.

**Pasos:**
1. Ingresar al sitio web.
2. Localizar la categoría SALCHICHONERÍA.
3. Seleccionar la categoría.

**Resultado esperado:** La página de la categoría debe abrir correctamente y mostrar los productos disponibles.

**Resultado obtenido:** La categoría abrió y funcionó correctamente.

**Estado:** PASS.

---

## CP-003 – Acceso a la categoría PANADERÍA

**Precondiciones:** El sitio web se encuentra disponible.

**Pasos:**
1. Ingresar al sitio web.
2. Localizar la categoría PANADERÍA.
3. Seleccionar la categoría.

**Resultado esperado:** La página de la categoría debe abrir correctamente y mostrar los productos disponibles.

**Resultado obtenido:** La categoría abrió y funcionó correctamente.

**Estado:** PASS.

---

## CP-004 – Acceso al carrito de compras

**Precondiciones:** El sitio web se encuentra disponible.

**Pasos:**
1. Ingresar al sitio web.
2. Localizar la opción del carrito de compras.
3. Seleccionar el carrito.

**Resultado esperado:** El carrito debe abrir correctamente sin mostrar errores de aplicación.

**Resultado obtenido:** El carrito abrió y funcionó correctamente.

**Estado:** PASS.

---

## CP-005 – Carga de la página principal

**Precondiciones:** Se cuenta con conexión a internet.

**Pasos:**
1. Ingresar a la dirección del sitio web.
2. Esperar a que cargue la página principal.
3. Revisar el contenido visible.

**Resultado esperado:** La página principal debe cargar y mostrar el contenido de la tienda.

**Resultado obtenido:** La página principal cargó y mostró el contenido esperado.

**Estado:** PASS.

---

## CP-006 – Navegación entre secciones principales

**Precondiciones:** El sitio web se encuentra disponible.

**Pasos:**
1. Ingresar a la página principal.
2. Utilizar el menú de navegación.
3. Seleccionar una sección disponible.
4. Regresar a la página principal.

**Resultado esperado:** La sección seleccionada debe abrir correctamente y permitir continuar navegando.

**Resultado obtenido:** La navegación entre las secciones disponibles funcionó correctamente.

**Estado:** PASS.

---

## CP-007 – Visualización del listado de productos

**Precondiciones:** Existe una categoría con productos disponibles.

**Pasos:**
1. Ingresar a una categoría.
2. Revisar el listado de productos.
3. Verificar que los productos se muestren correctamente.

**Resultado esperado:** Los productos disponibles deben mostrarse correctamente dentro de la categoría.

**Resultado obtenido:** El listado de productos se visualizó correctamente.

**Estado:** PASS.

---

## CP-008 – Apertura de un producto

**Precondiciones:** Existe al menos un producto disponible en el catálogo.

**Pasos:**
1. Ingresar a una categoría.
2. Seleccionar un producto disponible.
3. Revisar la página o vista de detalles.

**Resultado esperado:** La información del producto seleccionado debe abrir correctamente.

**Resultado obtenido:** El producto abrió y mostró su información correctamente.

**Estado:** PASS.

---

## CP-009 – Visualización de información del producto

**Precondiciones:** Se puede acceder a los detalles de un producto.

**Pasos:**
1. Seleccionar un producto.
2. Revisar la información mostrada.
3. Verificar que corresponda al producto seleccionado.

**Resultado esperado:** La información del producto debe mostrarse correctamente y corresponder al artículo seleccionado.

**Resultado obtenido:** La información del producto se visualizó correctamente.

**Estado:** PASS.

---

## CP-010 – Búsqueda de productos

**Precondiciones:** El sitio web cuenta con una función de búsqueda.

**Pasos:**
1. Localizar el campo de búsqueda.
2. Introducir el nombre de un producto disponible.
3. Ejecutar la búsqueda.
4. Revisar los resultados.

**Resultado esperado:** El sistema debe mostrar productos relacionados con la búsqueda o un mensaje adecuado cuando no existan resultados.

**Resultado obtenido:** La función de búsqueda se comportó correctamente.

**Estado:** PASS.

---

## CP-011 – Agregar un producto al carrito

**Precondiciones:** Existe un producto disponible y una opción para agregarlo al carrito.

**Pasos:**
1. Abrir un producto disponible.
2. Seleccionar la opción para agregar al carrito.
3. Abrir el carrito de compras.
4. Revisar su contenido.

**Resultado esperado:** El producto seleccionado debe agregarse correctamente al carrito.

**Resultado obtenido:** La funcionalidad para agregar productos al carrito se comportó correctamente.

**Estado:** PASS.

---

## CP-012 – Modificar la cantidad de un producto

**Precondiciones:** El carrito contiene un producto y cuenta con controles para modificar la cantidad.

**Pasos:**
1. Abrir el carrito de compras.
2. Localizar un producto.
3. Modificar la cantidad mediante los controles disponibles.
4. Revisar el contenido actualizado.

**Resultado esperado:** El carrito debe reflejar la cantidad seleccionada y actualizar el estado del producto o el total cuando corresponda.

**Resultado obtenido:** La modificación de cantidad se comportó correctamente.

**Estado:** PASS.

---

## CP-013 – Eliminar un producto del carrito

**Precondiciones:** El carrito contiene un producto y dispone de una opción para eliminarlo.

**Pasos:**
1. Abrir el carrito de compras.
2. Localizar un producto.
3. Seleccionar la opción para eliminarlo.
4. Revisar el contenido del carrito.

**Resultado esperado:** El producto eliminado ya no debe aparecer en el carrito.

**Resultado obtenido:** La funcionalidad para eliminar productos se comportó correctamente.

**Estado:** PASS.

---

## CP-014 – Regresar a la tienda desde el carrito

**Precondiciones:** El carrito de compras se encuentra disponible.

**Pasos:**
1. Abrir el carrito de compras.
2. Localizar la opción para continuar comprando o una navegación equivalente.
3. Seleccionar dicha opción.
4. Revisar la página de destino.

**Resultado esperado:** El usuario debe poder regresar a la tienda o a las categorías de productos.

**Resultado obtenido:** El regreso a la tienda funcionó correctamente.

**Estado:** PASS.

---

## CP-015 – Visualización del carrito vacío

**Precondiciones:** El carrito se encuentra vacío o se han eliminado todos sus productos.

**Pasos:**
1. Abrir el carrito de compras vacío.
2. Revisar el contenido mostrado.
3. Verificar que el carrito continúe siendo accesible.

**Resultado esperado:** El sitio debe mostrar un mensaje o estado adecuado indicando que el carrito no contiene productos.

**Resultado obtenido:** El estado del carrito vacío se comportó correctamente.

**Estado:** PASS.

---

## Resultados finales

| Estado | Total |
|---|---:|
| PASS | 15 |
| FAIL | 0 |
| BLOQUEADOS | 0 |
| TOTAL | 15 |

**Porcentaje de aprobación: 100%.**
