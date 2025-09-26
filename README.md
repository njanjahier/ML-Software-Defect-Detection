Diplomski rad – Primjena mašinskog učenja u otkrivanju defekata softvera

Ovo je praktični dio mog diplomskog rada. Projekat koristi Naivni Bajesov klasifikator da bi, na osnovu NASA CM1 dataseta, predvidio da li softverski modul sadrži defekt ili ne.

Opis projekta  
Učitavanje podataka iz cm1.csv  
Pretvaranje oznaka “defekt” / “nema defekta” u numeričke vrijednosti  
Podjela podataka na trening i test skup  
Treniranje Naive Bayes modela  
Prikaz rezultata kroz maticu konfuzije i izvještaj o klasifikaciji  
Crtanje grafikona matrice konfuzije radi vizualizacije

Korištene biblioteke  
pandas  
scikit-learn  
matplotlib  
seaborn  

Pokretanje u Google Colab-u  
1. Otvoriti Google Colab (https://colab.research.google.com/)  
2. Napraviti novi notebook ili otvoriti postojeći (npr. `01_ML_Defect_Detection_NASA_CM1.ipynb`)  
3. Učitati dataset cm1.csv (u Colab-u koristeći Upload opciju ili Google Drive)  
4. Instalirati biblioteke komandom:  
   `!pip install pandas scikit-learn matplotlib seaborn`  
5. Pokrenuti sve ćelije koda

Na izlazu se dobija  
Matrica konfuzije i izvještaj o performansama (preciznost, odziv, F1-score)  
Grafički prikaz matrice konfuzije

Struktura projekta  
`01_ML_Defect_Detection_NASA_CM1.ipynb` – glavni notebook sa kodom  
`requirements.txt` – lista biblioteka (za lokalno pokretanje)  
`README.md` – opis projekta  
`cm1.csv` – dataset (nije uključen zbog autorskih prava)

Napomena  
Projekat je urađen za diplomski rad na temu “Primjena tehnika mašinskog učenja u otkrivanju defekata softvera”. Testiran je u Google Colab okruženju, ali se može pokretati i lokalno ako instaliraš biblioteke iz `requirements.txt`.

Autor: Sanja Savić  
Godina: 2025
