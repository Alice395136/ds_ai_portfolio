## Aplikacja do inteligentnych notatek głosowych z Qdrant i AI
_Data utworzenia_: marzec 2025

Stworzyłam interaktywną aplikację webową do zarządzania notatkami, która wykorzystuje sztuczną inteligencję oraz bazę wektorową Qdrant. Aplikacja umożliwia nagrywanie, transkrypcję, wyszukiwanie oraz odtwarzanie notatek głosowych w prostym i intuicyjnym interfejsie.

### Główne funkcje aplikacji:
- **Nagrywanie notatek głosowych** bezpośrednio w przeglądarce
- **Automatyczna transkrypcja** mowy na tekst (np. z wykorzystaniem Whisper)
- **Odświeżanie tekstu po transkrypcji** – możliwość poprawienia/edycji tekstu
- **Wyszukiwanie semantyczne** notatek z użyciem **embeddingów**
- **Zapis i przechowywanie notatek** w bazie wektorowej Qdrant
- **Odtwarzanie nagranych notatek**
- Wykorzystanie modeli językowych do ulepszania jakości zapisu i wyszukiwania treści

Aplikacja została zbudowana z użyciem:
- **Streamlit** – frontend interaktywny
- **Qdrant** – baza wektorowa do przechowywania embeddingów
- **Whisper / Transformers** – do transkrypcji nagrań
- **OpenAI embeddings / Sentence Transformers** – do wyszukiwania semantycznego

 🔗 [Zobacz kod źródłowy na GitHubie](https://github.com/Alice395136/25_wdrozenie_aplikacji_notatki/blob/main/app.py)  



