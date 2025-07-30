Aquí tienes un **resumen explicativo y claro** para presentar esta demostración práctica sobre **cómo preparar un proyecto de desarrollo de IA en Azure AI Foundry**, ideal para una audiencia general o no técnica:

---

## 🛠️ **Demostración: Preparar un Proyecto de IA en Azure AI Foundry**

### 🎯 Objetivo

En esta actividad vamos a usar **Azure AI Foundry**, una plataforma que permite a equipos de desarrollo crear, probar y gestionar proyectos de inteligencia artificial generativa, como soluciones de chat, asistentes inteligentes, análisis de texto y más.

---

### 🔄 Paso a paso, explicado sencillo:

#### 1. **Entramos a Azure AI Foundry**

Abrimos la página [https://ai.azure.com](https://ai.azure.com) e iniciamos sesión con nuestra cuenta de Azure. Cerramos mensajes de ayuda para ver la pantalla principal.

#### 2. **Creamos un proyecto de IA**

* Buscamos el modelo **gpt-4o** (el modelo más avanzado de Azure OpenAI).
* Hacemos clic en **“Usar este modelo”**.
* Asignamos un nombre al proyecto y completamos los datos:

  * Elegimos un recurso de Foundry o creamos uno nuevo.
  * Seleccionamos una suscripción, grupo de recursos y región.

✅ Resultado: se crea un proyecto con el modelo listo para usar.

#### 3. **Configuramos el modelo**

* Si se solicita, desplegamos el modelo gpt-4o con un límite de **50,000 tokens por minuto** (esto evita exceder la cuota).
* Se abre automáticamente el **Chat Playground**, un entorno donde podemos probar cómo responde el modelo.

#### 4. **Revisamos la vista general del proyecto**

* Navegamos al menú lateral izquierdo y seleccionamos **Overview** para ver la página principal del proyecto.
* También accedemos al **Management center**, donde se gestiona tanto:

  * El **recurso de Azure AI Foundry** (acceso, conexión a otros servicios).
  * El **proyecto específico** (usuarios, modelos, endpoints).

#### 5. **Verificamos los recursos en el portal de Azure**

* Desde la vista general del recurso, seguimos el enlace al grupo de recursos.
* En el portal de Azure, vemos todos los servicios que se crearon automáticamente (modelos, almacenamiento, endpoints, etc.).

#### 6. **Exploramos los endpoints del proyecto**

* En la vista del proyecto, vemos las **claves y URL de acceso (endpoints)**, que se pueden usar para conectar una app a este modelo.

#### 7. **Probamos el modelo en el Playground**

* Vamos a la sección **Playgrounds > Chat Playground**.
* Asignamos una instrucción al modelo:

  ```
  You are a history teacher who can answer questions about past events all around the world.
  ```
* Escribimos una pregunta como:

  ```
  What are the key events in the history of Scotland?
  ```

✅ El modelo responde como si fuera un profesor de historia.

---

### 🧹 Limpieza final

Para evitar costos innecesarios:

* Ingresamos al portal de Azure.
* Buscamos el **grupo de recursos** que creamos.
* Seleccionamos **Eliminar grupo de recursos**.

---

### 🧠 ¿Qué aprendimos?

Con esta demostración aprendimos a:

* Crear un entorno de trabajo de IA en Azure.
* Probar y personalizar un modelo como GPT-4o.
* Ver cómo se organizan los recursos y accesos.
* Ejecutar pruebas reales con instrucciones y preguntas específicas.

