  🤖 Agente de IA Multimodal: Automatización para Grace Store
**n8n | Google Gemini | WhatsApp Business API | Groq | ngrok**

Este proyecto presenta una solución integral de automatización diseñada para optimizar las ventas y la atención al cliente de **Grace Store**. El agente gestiona flujos complejos de comunicación en redes sociales y WhatsApp, permitiendo una experiencia de compra automatizada, multimodal y eficiente.

## 🚀 Desafíos Técnicos Resueltos
* **Conectividad Local-Cloud:** Implementé **ngrok** para establecer un túnel seguro que permite recibir los webhooks de la API de Meta directamente en mi instancia local de **n8n**, garantizando una comunicación bidireccional en tiempo real.
* **Inteligencia Multimodal (Voz a Texto):** Integré la API de **Groq** (modelos Whisper) para procesar mensajes de voz de los clientes. Esto permite que el agente "escuche" los audios y responda de forma coherente en formato de texto.
* **Cerebro de Ventas:** Configuré **Google Gemini** como motor principal de procesamiento de lenguaje natural para asegurar respuestas humanas, personalizadas y estrictamente enfocadas en el cierre de ventas.
* **Persistencia de Datos:** El flujo orquestado en n8n sincroniza automáticamente las consultas, el inventario y el registro de prospectos con bases de datos y hojas de cálculo.

  🛠️ Stack Tecnológico
* **Orquestador:** n8n (Self-hosted).
* **IA Generativa:** Google Gemini.
* **Procesamiento de Audio:** Groq (Whisper).
* **Comunicación:** WhatsApp Business API.
* **Infraestructura:** ngrok para túneles de red.

**Proyecto desarrollado como parte de mi portafolio profesional en Ingeniería de Sistemas**
