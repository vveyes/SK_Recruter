<h1>SK_Recruter</h1>
<hr>

<h2>Установка и запуск</h2>

<p>Для работы с проектом выполните следующие шаги:</p>

<h3>1. Клонирование репозитория</h3>
<pre>
git clone https://github.com/vveyes/SK_Recruter.git
</pre>

<p>Далее в командной строке проекта:</p>

<h3>2. Создание виртуального окружения</h3>
<pre>
python -m venv .venv
.venv\Scripts\activate
</pre>

<h3>3. Обновление pip и установка зависимостей</h3>
<pre>
python -m pip install --upgrade pip
pip install -r requirements.txt
pip list --outdated
</pre>

<h3>4. Установка моделей SpaCy</h3>
<pre>
python -m spacy download ru_core_news_sm
python -m spacy download en_core_web_sm
</pre>
