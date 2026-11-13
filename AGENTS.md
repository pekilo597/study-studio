- Proyecto: Study Studio (app web local de estudio con lector de PDF, resúmenes, palabras clave, flashcards con repetición espaciada, quiz y enlaces compartibles).
- Stack: Vite + Vanilla JS (sin React/Vue), pdfjs-dist para extraer texto de PDFs y lz-string para comprimir temas en URLs compartibles.
- Seguridad: NUNCA hardcodear API keys ni usar .env. La Gemini API Key (modelo gemini-2.5-flash) se guarda exclusivamente en localStorage desde un modal de configuración.
- Diseño: Modo oscuro moderno, 100% responsivo (mobile-first) para estudiar cómodo en celular y PC.
- Respuestas cortas y directas; después de cada cambio importante, verifica que 
pm run build compile sin errores.
