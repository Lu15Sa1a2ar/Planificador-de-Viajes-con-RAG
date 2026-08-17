🧳✈️ Planificador de Viajes con RAG + LLM

Planificador de viajes personalizado que arma un itinerario día por día combinando datos reales de lugares con generación de texto por LLM. Trabajo práctico de la materia LLM Customization.

¿Qué hace?

Le contás:

📍 Destino (Buenos Aires, Nueva York o París)
📅 Cantidad de días
🎯 Intereses (cultura, arquitectura, gastronomía, etc.)
💰 Presupuesto
🥗 Restricciones (ej. vegetariano, movilidad reducida)

Y te devuelve un itinerario día por día, con horarios, lugares concretos y precios de referencia.

¿Cómo funciona?
RAG — más de 2.600 lugares reales de Buenos Aires, Nueva York y París, sacados de los portales de datos abiertos de cada ciudad, indexados con embeddings multilingües en ChromaDB.
LLM — Qwen2.5 (open source) toma los lugares recuperados por el RAG y arma el itinerario final, respetando formato y presupuesto.
Interfaz — Streamlit, corriendo directo desde Google Colab.
Demo

🎥 Ver video acá — (reemplazá este link por el del video)

Cómo correrlo
bash
git clone https://github.com/tu-usuario/nombre-del-repo.git
cd nombre-del-repo
pip install -r requirements.txt

Después abrí el notebook (.ipynb) en Google Colab, corré las celdas en orden (la primera vez arma el índice de ChromaDB con los datos de lugares) y se levanta la interfaz de Streamlit desde ahí mismo.

(Ajustá estos pasos si tu notebook arma las cosas en otro orden.)

Stack

Python · Streamlit · ChromaDB · Qwen2.5 · Sentence Transformers · Google Colab

Feedback

¿Qué le agregarían? Ideas, preguntas y sugerencias son bienvenidas — abran un issue o comenten en el posteo de LinkedIn.
