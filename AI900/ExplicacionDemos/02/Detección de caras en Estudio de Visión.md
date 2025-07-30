Perfecto. Aquí tienes una explicación lista para usar con personas no técnicas, que puedes presentar al hablar de esta cuarta demostración sobre detección de rostros en Vision Studio:

---

### 👥 **Demostración: Detección de Rostros con Azure AI Vision Studio**

En esta actividad vamos a ver cómo una computadora puede detectar **rostros humanos en una imagen**. Esto es muy útil en situaciones reales, como una tienda que quiere saber **dónde están los clientes** para poder asistirlos mejor.

Lo haremos con una herramienta visual llamada **Azure Vision Studio**, que nos permite usar inteligencia artificial sin necesidad de programar.

---

### 🔄 Paso a paso, explicado de forma sencilla:

1. **Creamos un recurso de Inteligencia Artificial en Azure**
   Es como darle a la IA los permisos para que pueda empezar a trabajar con imágenes.

2. **Entramos a Vision Studio**
   Usamos una plataforma en línea ([https://portal.vision.cognitive.azure.com](https://portal.vision.cognitive.azure.com)) que nos deja cargar imágenes y ver lo que la IA detecta en ellas.

3. **Seleccionamos la función para detectar rostros en imágenes**
   Aquí es donde la magia sucede: le damos una imagen a la IA, y ella nos dice si ve rostros, **dónde están ubicados**, y en algunos casos, **cuántas personas hay**.

4. **Probamos con imágenes reales de una tienda**:

   * 📷 *store-camera-1.jpg*: muestra personas comprando.
   * 📷 *store-camera-2.jpg*: más personas en otra parte de la tienda.
   * 📷 *store-camera-3.jpg*: personas, pero una de ellas está parcialmente oculta por una planta.

   La IA detecta automáticamente los rostros visibles y **nos da coordenadas de dónde se encuentran en la imagen**. Incluso nos muestra si no pudo detectar un rostro porque estaba tapado.

---

### 🧠 ¿Qué nos enseña esta demo?

Esta demostración muestra cómo una tienda puede:

* Saber cuántas personas hay en cada área.
* Detectar si alguien está esperando ayuda.
* Usar cámaras de forma más inteligente sin depender de vigilancia humana todo el tiempo.

Y todo esto se hace **sin escribir código**, usando herramientas visuales y amigables para cualquier persona.

---

### 🧹 Limpieza al final

Para evitar costos en la nube, al final **borramos los recursos creados**, como el proyecto de inteligencia artificial que usamos.

---
