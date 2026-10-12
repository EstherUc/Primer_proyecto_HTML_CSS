# Primer_proyecto_HTML_CSS
Ejercicio de una página sencilla para practicar conceptos de HTML y CSS.

# Pizzoleto
## Descripción
Pizzoleto es un prototipo web responsive (Mobile First) para una marca ficticia de pizzas.

Es una plataforma desde la que un usuario puede realizar pedidos para domicilio o recoger. También puede consultar los productos, las promociones y crear una cuenta de cliente.

El proyecto es un desarrollo de prototipo estático, las acciones como buscar, iniciar sesión o finalizar pedidos (entre otros) se representan visualmente pero no disponen de funcionalidad.

## Estructura del Prototipo

* **index.html:** Página principal de Pizzoleto. Presenta la identidad de la marca y permite al usuario acceder a las principales opciones de pedido (domicilio o recoger) y posible navegación por el menú, promos, pedido, iniciar sesión o crear una cuenta nueva.
  * Los enlaces que si tienen alguna funcionalidad son:
    * Crear cuenta.
    * Recoger (mitad derecha de la pizza).
    * Pedido
      
* **order_pickup.html:** Es la vista del catálogo de productos. Esta vista tiene las categorias (pizzas, entrantes, bebidas y postres), un buscador de productos, tarjetas de pizzas con el precio, la información y selector de cantidades, y por último, un resumen visual del pedido (en la versión web).

El menú del catálogo de productos es interactivo aunque no tiene funcionalidad.
* Los enlaces que si tienen alguna funcionalidad son:
    * El logo
    * Inicio
    * Pedido
      
* **new_account.html:** Página de creación de cuenta. Esta página contiene un formulario organizado por datos personales, datos de domicilio y contraseña. También tiene la aceptación de términos y condiciones.
El formulario detecta si no rellenas alguno de los campos, si no metes un email válido, si no pones un teléfono numérico de 9 cifras y la contraseña no la muestra. No se envía el formulario a ningún sitio al darle al botón "Crear cuenta", pero si hace esas comprobaciones.

  * Los enlaces que tienen alguna funcionalidad son:
    * El logo
    * Inicio
    * Pedido 
## Tecnologías Utilizadas
* HTML5
* CSS3
## Enfoque Técnico
Breve resumen de cómo se ha planteado el desarrollo:
* Diseño Mobile First.
* Uso de selectores básicos y combinados.
* Uso de diferentes valores de Display y Position.
## Autor
* **Esther Uclés**
