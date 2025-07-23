# pureb


## 🚀 Estructura del Proyecto
PrototipadoML/
│
├── modelo/
│ ├── pipeline_random_forest.pkl # Modelo para número de ofertas
│ ├── randomforest_sme.pkl # Modelo para PYME ganadora
│ ├── catboost_win_country.pkl # Modelo para país ganador
│ └── ... (otros modelos entrenados)
│
├── pages/
│ ├── 1_Prediccion_Ofertas.py # Página: Número de ofertas
│ ├── 2_Prediccion_PYME.py # Página: PYME ganadora
│ └── 3_Prediccion_Pais.py # Página: País adjudicatario
│
├── home.py # Página principal (predicción integral)
├── requirements.txt
├── README.md
