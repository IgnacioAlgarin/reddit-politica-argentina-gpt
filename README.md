# ¿Cómo se habla de política en Reddit Argentina? Un análisis con Python y GPT 

Este proyecto analiza el contenido del subreddit r/argentina en torno a las elecciones presidenciales de 2023. Se recolectaron publicaciones reales, se clasificaron automáticamente usando la API de ChatGPT y se visualizó la evolución semanal de menciones a Javier Milei.

---

## ⚙️ Stack usado

- Python + Colab
- PRAW (Reddit API)
- OpenAI GPT-3.5
- Pandas, Matplotlib, Seaborn

---

## 🧠 Clasificación de contenido

Se clasificaron 999 publicaciones usando prompts personalizados con la API de OpenAI. Las categorías más frecuentes incluyeron:

- Milei
- Cristina
- Macri
- Bullrich
- Ninguno

---

## 📈 Análisis temporal

Se analizó la frecuencia semanal de publicaciones mencionando a Milei desde 2017 a 2023. El pico máximo coincidió con las semanas electorales del segundo semestre de 2023.

---

## 📂 Estructura

- `/data`: dataset con los posts procesados
- `/notebooks`: código en Python (Google Colab)
- `/images`: visualizaciones generadas
