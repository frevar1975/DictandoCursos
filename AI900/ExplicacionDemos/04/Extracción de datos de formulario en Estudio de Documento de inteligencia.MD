Perfecto. Aquí tienes una explicación clara y adaptada para presentar esta última demostración del curso a una audiencia no técnica:

---

### 🧾📊 **Demostración: Extraer Datos de Recibos con Azure AI Document Intelligence**

En esta actividad aprenderemos cómo la inteligencia artificial puede **leer automáticamente documentos escaneados o fotografiados**, como facturas, boletas o recibos, y **extraer los datos importantes** (como el nombre del comercio, el total pagado, o la fecha de la transacción).

Esto lo haremos usando el servicio de **Azure AI Document Intelligence**, dentro de la plataforma visual **Azure AI Foundry**, sin necesidad de escribir código.

---

### 🔄 Paso a paso, explicado sencillo:

1. **Creamos un nuevo proyecto en Azure AI Foundry**
   Esto nos da acceso a las herramientas de visión artificial y documentos inteligentes.

2. **Entramos a la sección de “Vision + Document”**
   Es un área de pruebas donde podemos cargar imágenes de documentos para analizarlos.

3. **Seleccionamos el modelo especializado en recibos (“Receipts”)**
   Azure ya tiene modelos listos que entienden cómo se ven y qué información suelen tener los recibos.

4. **Cargamos una imagen de un recibo**
   Subimos una foto de ejemplo que contiene una compra hecha en una tienda ficticia llamada *Northwind Traders*.

5. **Ejecutamos el análisis con un clic (“Run Analysis”)**
   La inteligencia artificial lee el documento y automáticamente:

   * Encuentra el **nombre del comercio**, la **dirección**, el **teléfono**.
   * Extrae los **productos comprados**, **precios**, **impuestos** y el **total**.
   * Muestra estos datos en pantalla con **porcentaje de confianza**, para saber qué tan seguro está de cada dato detectado.

---

### 🧠 ¿Por qué esto es tan útil?

Porque **muchas empresas reciben miles de documentos** como estos y, en vez de capturar datos a mano, pueden:

* Automatizar la contabilidad.
* Leer facturas electrónicas de distintos países.
* Digitalizar documentos antiguos.

Todo eso de forma rápida, precisa y **sin intervención humana manual**.

---

### 🧹 Limpieza final

Cuando terminamos, **eliminamos los recursos creados en Azure** para no generar costos innecesarios.

---

### ✅ ¿Qué vimos en esta demostración?

* Cómo una IA no solo *lee* texto (como lo hace OCR), sino que **entiende la estructura** del documento.
* Cómo extrae datos que se pueden **guardar directamente en una base de datos o sistema de gestión**.
* Y lo mejor: cómo se puede hacer todo esto desde una interfaz visual, sin saber programar.

