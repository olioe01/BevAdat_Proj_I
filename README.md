# Tanulási szokások és vizsgaeredmények

Projektmunka a *Bevezetés az adattudományba* tárgyhoz.

Azt vizsgálom, hogy a diákok szokásai (tanulás, alvás, közösségi média, sport, mentális állapot stb.) hogyan függenek össze a vizsgapontszámukkal, és hogy mennyire jól becsülhető ez gépi tanulási modellekkel.

**Adathalmaz:** [Student Habits vs Academic Performance – Kaggle](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)

## Tartalom
- `tanulasi_szokasok_elemzes.ipynb` – a teljes elemzés (EDA, tisztítás, hipotézisek, feature engineering, regressziós és osztályozási modellek)
- `data/` – a nyers CSV
- `kepek/` – a notebook által generált ábrák

## Futtatás
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook tanulasi_szokasok_elemzes.ipynb
```
