# Bakalárska práca
Práca je zameraná na predikciu podvodov pri používaní samoobslužných pokladní za pomoci dátovej analytiky a strojového učenia.
Cieľom bolo správne klasifikovať čo najväčší počet podvodov za účelom zníženia strát obchodných reťazcov.

# Súbory
- systemova_prirucka.ipynb - zdrojový kód
- train.csv - dátová množina slúžiaca na trénovanie modelov
- trest.csv - dátová množina slúžiaca na testovaie klasifikácie modelov (aby bolo možné súbor nahrať na GitHub, bol komprimovaný do formátu ZIP, pred použitím je potrebná jeho extrakcia)
- real.csv - skutočné hodnoty atribútu fraud pre dáta v testovacej množine

# Spustenie
Kód je určený pre spustenie v Jupyter Notebook.

# Použité modely
- K-najbližších susedov (kNN)
- metóda podporných vektorov (SVM)
- rozhodovací strom
- náhodný les
- XGBoost
- logistická regresia
- Naive Bayes

# Výstup
- grafické zobrazenia rozdelenia a vzťahov atribútov
- výpisy so štatistických testov
- kontingenčné tabuľky klasifikácie pre jednotlivé algoritmy pred a po nadvzorkovaní
- výpočet zisku pri použítí daného modelu



