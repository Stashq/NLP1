# Analiza Języka Naturalnego (NLP) - zadanie 1

## Cel

Częściowo w oparciu o dostępne narzędzia i zasoby językowe należy zbu-dować (a raczej zestawić) program do analizy tekstów w języku polskim napoziomie wyrazów i ich własności gramatycznych. Program powinien podzielićtekst na poszczególne wyrazy i ujednoznacznić ich opis morfo-syntaktyczny.

1. Zbudowanie tokenizatora (programu do segmentacji tekstu na poziomiewyrazowym). Zakładamy zastosowanie prostego podziału na zdania, np.wybrane znaki interpunkcyjne wyznaczają koniec zdania. Tokenizator po-winien odróżniać potencjalne wyrazy języka od innych kategorii tokenów.

2. Zapoznanie się z analizatorem morfologicznym Morfeusz i zwracanym przezniego tagsetem. Można wykorzystać usługę sieciową CLARIN-PL udostęp-niającą Morfeusza.2

3. Zapoznanie się z dostępnymi tagerami morfo-syntaktycznymi dla językapolskiego. Porównanie działania trzech z nich na zbiorze testowym z kon-kursu PolEval.

4. Porównanie wpływu działania poszczególnych tagerów jako narzędzi wstęp-nego przetwarzania na wyniki klasyfikacji tekstów (korpus Wikipedii zCLARN-PL) za pomocą naiwnego algorytmu Bayesowskiego:(a) gdy do reprezentacji dokumentów są brane pod uwagę tylko rzeczow-niki,(b) tylko czasownik,(c) tylko przymiotniki.Należy zaproponować i uzasadnić własny sposób grupowanie klas grama-tycznych NKJP do części mowy.

5. Dodatkowe(dodatkowe punkty) Zbudowanie tagera głosującego w opar-ciu o połączenie kilku tagerów jednostko
