# SK_Recruter
---

## Установка и запуск

Для работы с проектом выполните следующие шаги:

# 1. Клонирование репозитория
git clone https://github.com/vveyes/SK_Recruter.git
cd SK_Recruter

# 2. Создание виртуального окружения
python -m venv .venv
.venv\Scripts\activate

# 3. Обновление pip и установка зависимостей
python -m pip install --upgrade pip
pip install -r requirements.txt
pip list --outdated

# 4. Установка моделей SpaCy
python -m spacy download ru_core_news_sm
python -m spacy download en_core_web_sm
