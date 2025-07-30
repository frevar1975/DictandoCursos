Perfecto. Aquí tienes una explicación clara y amigable, ideal para compartir con personas no técnicas durante la presentación de esta sexta demostración:

---

### ❓💬 **Demostración: Crear un Asistente de Preguntas Frecuentes con Inteligencia Artificial**

En esta actividad vamos a enseñarle a la inteligencia artificial a **responder preguntas frecuentes automáticamente**, como si fuera una persona atendiendo por chat. Todo esto lo haremos sin programar, usando una plataforma visual de Microsoft llamada **Language Studio**.

#### 🧠 ¿Qué haremos exactamente?

Vamos a tomar un documento real de preguntas frecuentes de una agencia de viajes ficticia (Margie’s Travel) y convertirlo en una **base de conocimiento inteligente**, es decir, un sistema que entiende lo que el usuario pregunta y da respuestas relevantes.

---

### 🔄 Paso a paso, explicado para todos:

1. **Creamos un recurso de lenguaje en Azure**
   Esto es como darle a la IA un cerebro especializado en comprensión de textos y preguntas.

2. **Entramos a Language Studio**
   Es una plataforma web donde podemos cargar documentos, agregar preguntas, probar respuestas, y todo sin escribir código.

3. **Creamos un nuevo proyecto de preguntas personalizadas (Custom Question Answering)**
   Le damos un nombre al proyecto, definimos el idioma, y cargamos un documento desde una URL que contiene las preguntas frecuentes.

4. **Revisamos y editamos la base de conocimiento**
   Podemos:

   * Ver las preguntas que se importaron automáticamente desde el documento.
   * Agregar nuestras propias preguntas y respuestas personalizadas, como por ejemplo:

     * **Pregunta:** Hello
     * **Respuesta:** Hi
     * (Incluso se pueden añadir variaciones como "Hiya" para entender distintos modos de decir lo mismo.)

5. **Entrenamos y probamos la IA**
   Es como hacerle preguntas para ver si entiende y responde bien. Por ejemplo:

   * *Hi* → Responde *Hi*
   * *I want to book a flight* → Da una respuesta útil sobre cómo hacerlo.
   * *How can I cancel a reservation?* → Busca la mejor respuesta en el documento cargado.

   Además, la IA muestra dos niveles de respuesta:

   * Una **respuesta corta** generada automáticamente.
   * Y un **fragmento más largo** del documento original donde aparece esa respuesta.

6. **Publicamos nuestro asistente**
   Cuando todo funciona bien, podemos hacer clic en "Deploy" para activarlo. Esto nos da una interfaz que podríamos conectar fácilmente a un sitio web o una app para atención al cliente.

---

### 🧩 ¿Por qué es útil esta demostración?

Porque **muchas empresas tienen documentos con información repetitiva** (FAQ, políticas, procedimientos) y podrían convertirlos en asistentes inteligentes que:

* Ahorren tiempo al personal de soporte.
* Mejoren la experiencia del cliente.
* Estén disponibles 24/7.

Y lo mejor: **no hace falta saber programar** para lograrlo con Azure Language Studio.

---

### 🧹 Limpieza final

Como siempre, al terminar **eliminamos los recursos creados** para evitar cobros innecesarios en la nube.


