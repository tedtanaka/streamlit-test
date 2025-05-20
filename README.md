# streamlit
Streamlit play project.

Streamlist is neat in that a simple Python script can create a simple web app, no need for model/view/controller, no HTML template files, etc.

The downside is that the pages are simple, any complex CSS requires embedded HTML inside of the st.markdown() function, which is ugly.

Not sure if Streamlit can do any Javascript or Ajax, I'm guessing not.

So the sweet spot is simple web apps with a simple, clean style.  The analogy is perhaps Notepad vs Microsoft Word.

To run in PyCharm:

Set up the virtual env:
* python -m venv venv
* venv\Scripts\activate.bat
* pip install -r requirements.txt

Run the app:
* streamlit run tutorial.py

Deactivate the venv:
* deactivate
