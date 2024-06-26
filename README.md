Ввести следующие команды в консоль (при первом запуске все, далее - при повторных запусках - выполнить только 4 шаг, модель сможет работать автономно т.к. все библиотеки ранее уже загружены):
python (or write py) -m venv venv
venv\Scripts\activate - для Windows
source venv/bin/activate - для Макбука
pip install -r requirements.txt
streamlit run app.py
