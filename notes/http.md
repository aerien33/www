
# telehack.com

komenda:	działanie:
today		wyświetla wydarzenia historyczne odpowiadające dzisiejszej dacie 
		(np. 7 października)
sudoku		rozpoczyna grę w sudoku
eliza		rozpoczyna rozmowę z psychoterapeutą AI



# curl
	
żądanie		metoda		ścieżka					kod			3 nagłówki + co znaczą
info.cern.ch	GET		info.cern.ch				200 OK			Date (data), Server (rodzaj serwera), 
												Last-Modified (data ostatniej modyfikacji strony)
github.com	HEAD		github.com				301 Moved Permanently 	Content-Length (rozmiar odpowiedzi w bajtach, <body>), 
												Location (ścieżka do strony docelowej)
nie-ma-takiej	HEAD		- 					404 Not Found		Connection (stan połączenia między klientem a serwerem),
												Content-Type (rodzaj przesłanej odpowiedzi w <body>)
						

# sekcja zwłok

pomiar 			info.cern.ch		spacejam.com/1996	onet.pl
liczba żądań		2			20			456
przesłane dane		2.5 kB			235 kB			5.1 MB
czas ładowania		83 ms			894 ms			1.11 s
elementy DOM		16			119			1569
najcięższy plik (typ)	vnd.microsoft.icon	script			script

Co mnie zaskoczyło?
że najcięższy plik na stronie Onetu to skrypt, a nie jakiś rodzaj mediów (np. video)
spodziewałam się też mniejszej liczby elementów DOM na stronie spacejam.com

