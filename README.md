# SETUP VIRTUAL ENVIRONMENT

mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt

# BUAT FILE PROYEK
buat file proyek dashboard.py, kemudian Letakkan dataset orders_data.csv dan merged_payment_data.csv di folder proyek_analisis_data

# RUN STREAMLIT
streamlit run dashboard.py
