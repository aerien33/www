## Devlog Notes

### Co zrozumiałam o pudełkach i układzie?

- warto na początku ustawić do wszystkich elementów "box-sizing: border-box", aby zwiększyć przewidywalność zachowania odstępów i marginesów w pudełkach 
- za pomocą narzędzi grid i flexbox można w szybki sposób zarządzać układem strony
- grid-templates jest dobrym sposobem na ustawienie głównego układu strony
- flexbox lepiej nadaje się do ustawienia mniejszych elementów względem siebie
- zmiana jednej linijki w CSS potrafi wiele zmienić w układzie strony


### Co sprawiło trudność?

- zmiany odstępów przy większym poziomie zagnieżdżenia elementów
- nieumyślne nachodzenie na siebie dwóch elementów, które mają position: sticky
- rozróżnienie błędnych ustawień pudełka (margins, padding) od problemów z grid-template
- zgranie różnych odcieni kolorów tekstu i tła w celu zachowania czytelności strony
