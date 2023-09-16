# ML_project2023

Ovaj rad predstavlja završni projekat kursa Mašinsko učenje 2023. godine na Matematičkom fakultetu, Univerziteta u Beogradu.

Autor: Pavle Savić (broj indeksa: 1075/2022)

Osnovna ideja projekta jeste uporedna analiza performansi različitih modela Mašinskog učenja na problemu analize sentimenta. 
Za tu namenu korišćen je skup podataka IMDB Dataset preuzet sa Kaggle platforme koji se sastoji od 50 hiljada komentara na filmove: 25 hiljada pozitivnih i 25 hiljada negativnih.

U svesci 01 urađena je osnovna analiza i vizuelizacija statistika i svojstava posmatranog skupa.
Sveska 02 približava različite koncepte vektorizacije tekstualnih podataka a potom i izbor hiperparametara i analizu performansi tradicionalnih modela mašinskog učenja (logistička regresija, metod potpornih vektora, k najbližih suseda)
U svasci 03 implementiran je BERT transformer.

Korišćene biblioteke: numpy, pandas, matplotlib, nltk, wordcloud, sklearn, tensorflow, keras, transformers
Instalacija transformers biblioteke:
anaconda:
conda install -c conda-forge transformers
pip:
pip install transformers

Korišćena literatura:
https://medium.com/@Mirza_Yusuf/using-a-bert-model-for-sentiment-analysis-6c6fcc106843
https://www.geeksforgeeks.org/sentiment-classification-using-bert/
