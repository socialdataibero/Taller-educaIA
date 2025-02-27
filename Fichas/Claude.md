# :RiApps2AddFill: Claude: _modelos y aplicación_

> [!question]+ **¿Qué es?**  
> Es un **modelo de lenguaje de IA** (similar a ChatGPT) creado por la empresa _Anthropic_.
>
> - star! **Asistente virtual** capaz de mantener conversaciones, responder preguntas y ayudar en tareas de escritura, codificación y análisis de datos.
> - lk! Accede a la aplicación web de Claude [**AQUÍ**](https://claude.ai/new).

---
## :LiStarList: Características principales

- int! **Énfasis en seguridad y alineación ética**: utiliza un enfoque llamado _IA Constitucional_, donde el modelo sigue un conjunto de principios guía (“constitución”) para autocorregir sus respuestas y evitar contenidos nocivos​
- esca! **Ventanas de contexto grandes**: en sus versiones más recientes, puede manejar hasta _100,000 tokens_ (unas 75 mil palabras) de contexto​.
- gen! **Memoria conversacional extensa**: teniendo más capacidad para recordar el contexto de un conversación que sus principales competidores (chatGPT).
- data! **Destaca en programación y análisis de datos**.

---
## :FasCubes: Modelos

> [!vs] **Tres generaciones de modelos**: 1, 2 y 3.

> [!important] **Dentro de cada generación, puede haber mejoras menores indicadas con decimal**  (ej. 2.1 es una versión refinada de 2.0)

En las generaciones más actuales (_Claude 3_) se utilizaron las siguientes etiquetas para determinar el funcionamiento de los modelos:

- esca! Haiku = rápido
- standar! Sonnet = equilibrado
- task! Sonnet = equilibrado

Estos tres modelos más recientes, tienen las siguientes características:

| Modelo              | Descripción                                                                                            | Ventana de Contexto | Uso Ideal                                                                                                     | Características Adicionales                                                                                   |     |
| ------------------- | ------------------------------------------------------------------------------------------------------ | ------------------- | ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | --- |
| **Claude 3 Haiku**  | Modelo rápido y eficiente, sucesor de “Instant”. Ideal para consultas breves o conversaciones ligeras. | 200K tokens         | Chats interactivos, asistentes en vivo donde la velocidad es crítica. Variante de menor costo.                | Respuestas casi instantáneas, calidad decente.                                                                |     |
| **Claude 3 Sonnet** | Modelo equilibrado (all-rounder). Balance entre rendimiento y velocidad.                               | 200K tokens         | Aplicaciones profesionales y empresariales, soporte al cliente, codificación, análisis de datos.              | Versión 3.5 amplía respuestas a 8192 tokens (~6200 palabras) y actualiza conocimiento hasta mediados de 2024. |     |
| **Claude 3 Opus**   | Modelo de máxima capacidad y profundidad. Enfocado en tareas complejas y abiertas.                     | 200K tokens         | Problemas que requieren razonamiento extenso, análisis exhaustivo, redacción creativa o revisión estratégica. | Alta calidad y detalle en respuestas, rendimiento superior pero más lento y costoso.                          |     |

---

## :LiMousePointerClick: Interfaz de Usuario

La aplicación web de Claude, se compone de 3 partes principales:

![[claude_gui.png]]


> [!side]- **Menú lateral**  
> 
> Permite acceder al historial de conversaciones, crear nuevos chats y acceder a las configuraciones del perfil.

> [!conversation]- **Barra de búsqueda**  
> El usuario ingresa sus solicitudes escritas por este medio, permitiendo la interacción directa con el modelo seleccionado. 

> [!search]- **Menú de opciones**  
> Permite seleccionar distintas configuraciones:
> 1. Selector de modelo
> 2. Cambiar el estilo de respuesta.
> 3. Opciones colaborativas.

---
## :FasUniversalAccess: Accesibilidad: Planes

> [!pay] **Ofrece dos versiones: _una gratuita_ y otra de pago llamada _Claude pro_.**

- 🆓 **Plan gratuito**: **Acceso a la mayoría de funcionalidades**, pero con _limites de uso diario_. Se estima un uso de _40 mensajes cortos_ por día, sin embargo, este límite depende directamente de la demanda en servidores.
- :RiPaypalFill: **Claude pro**: Cuesta alrededor de **$20 USD al mes**, e incluye un límite mayor de uso y prioridad ante demanda de servidores. Además, acceso a funcionalidades nuevas y avanzadas.

---
## :RiFunctionAddFill: Funcionalidades interesantes para investigación

> [!missing] **Los LLMs tienen a usar escrituras poco natural o mecánico**

- :FasFileWord: **Ajuste de modelo y estilo**: Se permite cambiar el _estilo de escritura_ de las respuestas de _Claude_. Esto significa que puedes, por ejemplo, configurar a Claude para que responda siempre de forma **concisa** o **formal** sin tener que pedírselo cada vez​. Posee diferentes opciones predefinidas, sin embargo, puedes cargar ejemplos propios e imitar el estilo, otorgando una herramienta de escritura valiosa para investigadores.

---
## :LiPenBox: Tutorial: _Investigación inicial sobre cualquier tema_

Una de las funciones más interesantes de Claude es la posibilidad de **personalizar el estilo de sus respuestas**. Esto se logra mediante la opción _“Choose Style”_ en la interfaz, que te permite seleccionar estilos predefinidos o incluso crear uno propio para que Claude adopte cierto tono o forma de redactar. A continuación, presentamos un tutorial detallado, paso a paso, sobre cómo usar esta característica

### Paso 1: Ubicar el menú de estilos

> [!tip] **Ubicación del menú de estilos**
> 
> - En la ventana de chat de Claude, encuentra la opción **“Choose style”** junto al nombre del modelo (ej. “Claude 3.5” o “Claude Haiku”).
> - Al hacer clic, se despliega una lista de estilos disponibles.

---

### Paso 2: Seleccionar un estilo predefinido

Claude ofrece varios **estilos predefinidos** que puedes aplicar con un clic:

> [!note] **Estilos predefinidos disponibles**
> 
> - **Normal**: Estilo neutro, balanceado y estándar de Claude.
> - **Concise (Conciso)**: Frases cortas y directas, ideal para respuestas rápidas.
> - **Formal**: Tono profesional y estructurado, ideal para escritos serios o académicos.
> - **Explanatory (Explicativo)**: Respuestas didácticas y detalladas, estilo profesor explicando.

> [!example] **Cómo seleccionar un estilo**
> 
> - Haz clic en _Choose style_ y selecciona el estilo deseado.
> - La respuesta cambiará de tono a partir del siguiente mensaje que envíes.
> - Puedes cambiar de estilo en cualquier momento durante la conversación.

---

### Paso 3: Cambiar o quitar el estilo

> [!tip] **Cambios de estilo**
> 
> - Puedes alternar entre los estilos predefinidos o personalizados cuantas veces quieras.
> - Para volver al comportamiento neutral, selecciona _Normal_ en el menú.

---

### Paso 4: Crear un estilo personalizado

Claude te permite crear un estilo personalizado utilizando dos métodos:

#### Método 1: A partir de ejemplos escritos

> [!example] **Pasos para crear un estilo a partir de ejemplos**
> 
> 1. Selecciona _“Add Writing Example”_ en _Create & Edit Styles_.
> 2. Sube un archivo (PDF, DOCX, TXT) o pega un fragmento de texto representativo. Para este ejemplo, usaremos este ejemplo:
> ```
> La inteligencia artificial (IA) tiene el potencial de cambiar muchos aspectos de la práctica sanitaria. La discriminación y la clasificación de imágenes tiene muchas aplicaciones dentro de la medicina. Se han desarrollado algoritmos de aprendizaje automático y redes neuronales complicadas para entrenar a una computadora a diferenciar las áreas normales de las anormales. El aprendizaje automático es una forma de IA que permite que la plataforma mejore sin ser programada. El diagnóstico asistido por computadora (CAD) se basa en latencia, que es el tiempo entre la imagen capturada y cuando es mostrada en la pantalla. La endoscopia asistida por IA puede incrementar la tasa de detección al identificar lesiones obviadas. Un sistema CAD de IA debe ser sensible, específico, con interfaces fáciles de usar, y proporcionar resultados rápidos sin prolongar sustancialmente los procedimientos. La IA tiene el potencial de ayudar tanto a endoscopistas entrenados como a los que están en entrenamiento. En vez de ser un sustituto para una técnica de alta calidad, deberá servir como un complemento de las buenas prácticas. La IA ha sido evaluada en tres escenarios clínicos en las neoplasias colónicas: la detección de pólipos, su caracterización (adenomatosos vs. no adenomatosos) y la predicción de cáncer invasor dentro de una lesión polipoide.
> ```
> 1. Haz clic en **“Create style”**. Claude analizará el tono y lenguaje del ejemplo.
> 2. Nombra el estilo y estará disponible en el menú de estilos personalizados.
> 3. Prueba el estilo con las ideas sugeridas.

#### Método 2: Describiendo el estilo deseado

> [!example] **Pasos para describir un estilo**
> 
> 1. Selecciona _“Describe style instead”_ en _Create Custom Style_.
> 2. Elige un preset como punto de partida (ej. Formal, Concise).
> 3. Proporciona instrucciones detalladas del tono o formato deseado.
> 4. Haz clic en **“Create style”** y el nuevo estilo aparecerá en tu lista.

> [!tip] **Consejos para describir un estilo**
> 
> - Especifica el tono (ej. “Amigable pero profesional”, “Sarcástico”).
> - Define la estructura (ej. “Responde en viñetas”, “Concluye con un resumen”).
> - Indica formalidad (ej. “Usa tercera persona”, “Tú o Usted según contexto”).
> 
> Por ejemplo:
> 
> ```
> 1. **Adopta un tono amigable pero formal**:  
>      
>    - Mantén un lenguaje respetuoso y profesional, sin perder cercanía ni calidez.  
>    - Evita el uso excesivo de jerga técnica o expresiones demasiado coloquiales.  
>      
> 2. **Organiza las ideas en viñetas siempre que sea posible**:  
>      
>    - Utiliza viñetas para estructurar información relevante de manera clara y concisa.  
>    - Prioriza la claridad y el orden en la presentación de las ideas, facilitando la lectura y comprensión del mensaje.  
>      
> 3. **Emplea la primera persona**:  
>      
>    - Redacta utilizando la primera persona del singular (“yo”) para transmitir un tono más personal y cercano.  
>    - En comunicaciones grupales, considera el uso de la primera persona del plural (“nosotros”) cuando corresponda.  
> ```

---

### Paso 5: Guardar y aplicar el estilo personalizado

> [!note] **Gestionar estilos personalizados**
> 
> - Puedes crear múltiples estilos y renombrarlos o eliminarlos según lo necesites.
> - Accede a ellos desde el menú _Choose Style_ bajo _Custom Styles_.
> - Para editar un estilo creado, ve a _Create & Edit Styles_ y ajusta las instrucciones.

> [!example] **Ejemplos de estilos personalizados**
> 
> - _“Poético”_: Usa metáforas y lenguaje florido para descripciones evocadoras.
> - _“Programador Estricto”_: Respuestas breves y técnicas, sin explicaciones largas.
> - _“Casual MX”_: Uso de modismos y expresiones coloquiales mexicanas.

---
## Referencias y recursos

1. What Is Claude AI? | Built In, fecha de acceso: febrero 24, 2025, [https://builtin.com/articles/claude-ai](https://builtin.com/articles/claude-ai)

2. What is Claude AI, and how does it compare to ChatGPT? - Pluralsight, fecha de acceso: febrero 24, 2025, [https://www.pluralsight.com/resources/blog/ai-and-data/what-is-claude-ai](https://www.pluralsight.com/resources/blog/ai-and-data/what-is-claude-ai)

3. Intro to Claude - Anthropic API, fecha de acceso: febrero 24, 2025, [https://docs.anthropic.com/en/docs/intro-to-claude](https://docs.anthropic.com/en/docs/intro-to-claude)

4. Claude 3.5: A guide to Anthropic's AI models and chatbot - Zapier, fecha de acceso: febrero 24, 2025, [https://zapier.com/blog/claude-ai/](https://zapier.com/blog/claude-ai/)

5. Claude AI 101: What It Is and How It Works - Grammarly, fecha de acceso: febrero 24, 2025, [https://www.grammarly.com/blog/ai/what-is-claude-ai/](https://www.grammarly.com/blog/ai/what-is-claude-ai/)

6. Anthropic Claude: Features Benchmarks Versions API Tutorial - Acorn Labs, fecha de acceso: febrero 24, 2025, [https://www.acorn.io/resources/learning-center/anthropic-claude/](https://www.acorn.io/resources/learning-center/anthropic-claude/)

7. Bard vs ChatGPT vs Claude: Which is the best AI Assistant in 2024? - Fliki, fecha de acceso: febrero 24, 2025, [https://fliki.ai/blog/bard-vs-chatgpt-vs-claude](https://fliki.ai/blog/bard-vs-chatgpt-vs-claude)

8. Comparing ChatGPT, Bard, Claude, Gemini: LLMs | Medium, fecha de acceso: febrero 24, 2025, [https://medium.com/@DigitalQuill.ai/comparative-analysis-between-chatgpt-bard-claude-and-gemini-ai-llms-30b7a4488c5d](https://medium.com/@DigitalQuill.ai/comparative-analysis-between-chatgpt-bard-claude-and-gemini-ai-llms-30b7a4488c5d)

9. An In-depth Comparison: ChatGPT vs. Claude vs. Bard | Winston AI, fecha de acceso: febrero 24, 2025, [https://gowinston.ai/an-in-depth-comparison-chatgpt-vs-claude-vs-bard/](https://gowinston.ai/an-in-depth-comparison-chatgpt-vs-claude-vs-bard/)

10. chihebnabil/claude-ui: A modern chat interface for Anthropic's Claude AI models built with Nuxt.js. Experience seamless conversations with Claude in a clean user interface. - GitHub, fecha de acceso: febrero 24, 2025, [https://github.com/chihebnabil/claude-ui](https://github.com/chihebnabil/claude-ui)

11. Claude, fecha de acceso: febrero 24, 2025, [https://claude.ai/](https://claude.ai/)

12. What Chat Interface are you using with Claude? : r/ClaudeAI - Reddit, fecha de acceso: febrero 24, 2025, [https://www.reddit.com/r/ClaudeAI/comments/1hn1rub/what_chat_interface_are_you_using_with_claude/](https://www.reddit.com/r/ClaudeAI/comments/1hn1rub/what_chat_interface_are_you_using_with_claude/)

13. I Built a Claude Chat UI Because I Was Tired of the Official Limitations | Codementor, fecha de acceso: febrero 24, 2025, [https://www.codementor.io/@chihebnabil/i-built-a-claude-chat-ui-because-i-was-tired-of-the-official-limitations-2lxqr345lk](https://www.codementor.io/@chihebnabil/i-built-a-claude-chat-ui-because-i-was-tired-of-the-official-limitations-2lxqr345lk)

14. Claude “Computer Use” Demo - Here's What Nobody's Telling You! - YouTube, fecha de acceso: febrero 24, 2025, [https://www.youtube.com/watch?v=W4l0eIOVQ9E](https://www.youtube.com/watch?v=W4l0eIOVQ9E)

15. A Quick Chat With Claude 3.5 Sonnet - YouTube, fecha de acceso: febrero 24, 2025, [https://www.youtube.com/watch?v=lDZsZriCwoY](https://www.youtube.com/watch?v=lDZsZriCwoY)

16. How to use Claude: Anthropic's AI Chatbot! #87 - YouTube, fecha de acceso: febrero 24, 2025, [https://www.youtube.com/watch?v=VIJQT9HsbCo](https://www.youtube.com/watch?v=VIJQT9HsbCo)

17. www.pluralsight.com, fecha de acceso: febrero 24, 2025, [https://www.pluralsight.com/resources/blog/ai-and-data/what-is-claude-ai#:~:text=Claude%2C%20developed%20by%20Anthropic%20AI,code%2Dwriting%2C%20and%20more.](https://www.pluralsight.com/resources/blog/ai-and-data/what-is-claude-ai#:~:text=Claude%2C%20developed%20by%20Anthropic%20AI,code%2Dwriting%2C%20and%20more.)

18. How to Use Claude AI Full Guide (2024) - Jamie AI, fecha de acceso: febrero 24, 2025, [https://www.meetjamie.ai/blog/how-to-use-claude](https://www.meetjamie.ai/blog/how-to-use-claude)

19. How Entrepreneurs Can Use Claude to Boost Productivity - Medium, fecha de acceso: febrero 24, 2025, [https://medium.com/the-ai-entrepreneurs/how-entrepreneurs-can-use-claude-to-boost-productivity-ebecef1098c3](https://medium.com/the-ai-entrepreneurs/how-entrepreneurs-can-use-claude-to-boost-productivity-ebecef1098c3)

20. Claude for Teams: What You Need to Know - Section School, fecha de acceso: febrero 24, 2025, [https://www.sectionschool.com/blog/claude-for-teams](https://www.sectionschool.com/blog/claude-for-teams)

21. Team up with Claude - Anthropic, fecha de acceso: febrero 24, 2025, [https://www.anthropic.com/team](https://www.anthropic.com/team)

22. Collaborate with Claude on Projects - Anthropic, fecha de acceso: febrero 24, 2025, [https://www.anthropic.com/news/projects](https://www.anthropic.com/news/projects)

23. How To Get the Most out of Claude AI - DreamHost, fecha de acceso: febrero 24, 2025, [https://www.dreamhost.com/blog/claude-ai/](https://www.dreamhost.com/blog/claude-ai/)

24. Anthropic Claude AI: Pricing and Features - Latenode, fecha de acceso: febrero 24, 2025, [https://latenode.com/blog/claude-ai-pricing-and-features](https://latenode.com/blog/claude-ai-pricing-and-features)