Diplomski rad – Primjena mašinskog učenja u otkrivanju defekata softvera

Ovo je praktični dio diplomskog rada. Projekat koristi Naivni Bajesov klasifikator (Naive Bayes) da bi se na osnovu NASA CM1 dataseta predvidjelo da li softverski modul sadrži defekt ili ne.

Opis projekta:
- učitavanje podataka iz cm1.csv
- pretvaranje oznaka "defekt" / "nema defekta" u numeričke vrijednosti
- podjela podataka na trening i test skup
- treniranje Naive Bayes modela
- prikaz rezultata kroz maticu konfuzije i izvještaj o klasifikaciji
- crtanje grafikona matrice konfuzije radi lakše vizualizacije

Korištene biblioteke:
- pandas
- scikit-learn
- matplotlib
- seaborn

Pokretanje u Google Colab-u:
1. Otvoriti Google Colab (https://colab.research.google.com/)
2. Napraviti novi notebook
3. Kopirati kod iz model.py u notebook
4. Učitati dataset cm1.csv (opcija "Upload" u Colab-u)
5. Instalirati potrebne biblioteke komandom:
   !pip install pandas scikit-learn matplotlib seaborn
6. Pokrenuti sve ćelije redom

Na izlazu se dobija:
- matrica konfuzije i izvještaj o performansama (preciznost, odziv, F1-score)
- grafički prikaz matrice konfuzije

Struktura projekta:
- model.py – glavni kod
- requirements.txt – spisak biblioteka (za lokalno pokretanje)
- README.md – opis projekta
- cm1.csv – dataset (nije uključen)

Napomena:
Projekat je urađen u okviru diplomskog rada na temu „Primjena tehnika mašinskog učenja u otkrivanju defekata softvera“. Testiran je u Google Colab okruženju, ali se može pokretati i lokalno uz instalaciju biblioteka iz requirements.txt.

Autor: Sanja Savić  
Godina: 2025
