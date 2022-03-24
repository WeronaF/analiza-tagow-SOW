# Systemy-organizacji-wiedzy-API
Program do analizy tagów zgromadzonych ze strony lubimyczytac.pl.

Jak powinien wyglądać zbiór danych? (3 pliki csv)

1. df_main:
* kolumna 'tytuł'
* kolumna 'tagi' (separator ustalany w separator_main)
* puste komórki pozostawione bez wartości

2. df_refined (opcjonalny zbiór danych, po ujednoliceniu w OpenRefine):
* kolumna 'tagi' (separator ustalany w separator_refined)
* puste komórki pozostawione bez wartości

3. kategoryzacja (zbiór unikatowych tagów z przypisaną kategorią):
* kolumna 'tagi'
* kolumna 'kategoria'- nazwy kategorii nie mogą zawierać przecinków (tematy, pojęcia -> Tematy i pojęcia)
