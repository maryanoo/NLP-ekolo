# NLP-ekolo

 Najstarsza inspiracja dla realizacji tego projektu to wpis z 2012 roku na blogu, niestety już bez wykresów, http://smarterpoland.pl/index.php/2012/02/piatek-chmura-slow-textmining-morfologik-i-oczywiscie-r/
 
## Projekt analizy językowej budżetów partycypacyjnych. 


### Plik główny budzety_obywatelskie.xlsx

Arkusz 1 - zawiera tytuły (nagłówki) projektów budżetów partycypacyjnych z 66 miast na prawach powiatu z lat 2018-2020. Dane zostały zebrane przeze Macieja Foltę i Mariusza Piotrowskiego w listopadzie 2020. Dane były pobierane ze stron internetowych miast (w tym archiwów prasowych, w przypadku braku innych źródeł). Struktura danych w arkuszu to rok, kiedy dany projekt pojawił się w głosowaniu, miasto, czyli gdzie został on złożony i nazwa, czyli tytuł projektu.

Ostatnia kolumna - to informacja, ile razy w kolumnie nazwa pojawiło się słowo kluczowe.

słowa podstawowe - to lista słów kluczowych (53 - formy podstawowe - lemma), które pojawiły się w badanym korpusie, i zaklasyfikowaliśmy, że należy do kategorii <ekologia>

filtrowanie - lista różnych form fleksyjnych, które były poszukiwane w nagłówkach - PRAWDA/FAŁSZ - potrzebne do zliczenia i wyodrębnienia, tylko tych projektów, które spełniały warunek - w nazwie pojawia się słowo kluczowe z arkusza słowa podstawowe

arkusz 3 - tabela przestawna ze zliczeniem miejscowości i lat, kiedy pojawiły się projekty <ekologiczne>

### Plik analiza_jezykow_budzetow.xlsx 
Wynik analiz korpusów budżetów partycypacyjnych przy użyciu własnego słownika języka polskiego i programu Antconc (Anthony, L. (2020). AntConc (Version 3.5.9) [Computer Software]. Tokyo, Japan: Waseda University. Available from https://www.laurenceanthony.net/software). Sposób pracy, oraz sam słownik, prezentuję na stronie - http://ozkultura.pl/node/7357. Zawartość arkuszy to informacje o frekwencji poszczególnych słów - w formacie forma podstawowa - lemma i formy fleksyjne.

### Folder korpus
Zawiera 3 pliki tekstowe z samymi nazwami projektów - służyły one do stworzenia pliku analiza_językowa_budżetów

## To-do-list/Pomysły
[ ] wyodrębnienie klastrów, ze względu na rok, na miejsce 

[ ] analiza kluczowości słów - względem określonego korpusu(?)

[ ] wyodrębnienie części zdań - lista frekwencyjna z określeniem liczby czasowników, rzeczowników, itd.

[ ]