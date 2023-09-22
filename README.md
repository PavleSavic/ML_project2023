# ML_project2023

Ovaj rad predstavlja završni projekat kursa Mašinsko učenje 2023. godine na Matematičkom fakultetu, Univerziteta u Beogradu.

Autor: **Pavle Savić** (broj indeksa: **1075/2022**)

Osnovna ideja projekta jeste uporedna analiza performansi različitih modela mašinskog učenja na problemu **analize sentimenta**. <br />
Za tu namenu korišćen je skup podataka **IMDB Dataset** preuzet sa Kaggle platforme koji se sastoji od 50 hiljada komentara na filmove: 25 hiljada pozitivnih i 25 hiljada negativnih.

U svesci [01](https://github.com/PavleSavic/ML_project2023/blob/main/01_Inicijalna_analiza_skupa.ipynb) urađena je osnovna analiza i vizuelizacija statistika i svojstava posmatranog skupa. <br />

Sveska [02](https://github.com/PavleSavic/ML_project2023/blob/main/02_Vektorizacija_Modeli.ipynb) približava različite koncepte **vektorizacije** tekstualnih podataka a potom i izbor hiperparametara i analizu performansi tradicionalnih modela mašinskog učenja (**logistička regresija**, **metod potpornih vektora**, **k najbližih suseda**). <br />

U svesci [03](https://github.com/PavleSavic/ML_project2023/blob/main/03_Transformer.ipynb) implementiran je **BERT transformer**.

U svesci [04](https://github.com/PavleSavic/ML_project2023/blob/main/04_demo_simple_gui.ipynb) implementirana je jednostavna **GUI aplikacija** u svrhu demonstracije.

<img width="1013" alt="transformers" src="https://github.com/PavleSavic/ML_project2023/assets/64799270/4e9d74fc-e087-4f74-85ae-eb5c6345dfa4">


Korišćene biblioteke: numpy, pandas, matplotlib, nltk, wordcloud, sklearn, tensorflow, keras, transformers, tkinter (za GUI) <br />

Instalacija transformers biblioteke: <br />
anaconda:
**conda install -c conda-forge transformers** <br />
pip:
**pip install transformers**

Instalacija tkinter biblioteke: <br />
anaconda:
**conda install -c anaconda tk** <br />
pip:
**pip install tk**


Korišćena literatura:
<br />https://www.analyticsvidhya.com/blog/2021/11/an-introduction-to-stemming-in-natural-language-processing/
<br />https://www.datacamp.com/tutorial/stemming-lemmatization-python
<br />https://medium.com/@Mirza_Yusuf/using-a-bert-model-for-sentiment-analysis-6c6fcc106843 
<br />https://www.geeksforgeeks.org/sentiment-classification-using-bert/
