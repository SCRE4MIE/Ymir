# Dokumentacja Discord Bota Ymir
### ***SCREAMIE#9946***

| Ymir_help | pokazuje aktualny prefix na serwerze |
| :--- | :--- |

#### Komendy podstawowe:  

| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :--- |:--- | :--- |
| **%hi** | | wysyła informacje o bocie | |
| **%poke** *@user* | | wysyła wiadomość poke do wzkazanego użytkownika | |
| **%say** *text* | | tworzy wpisany text w formie ramki | |
| **%zmienprefix** *prefix* | | ustawia prefix bota na *prefix* | administrator |
| **%clear** | **%clear** *n* | usuwa 1 wiadomość \| *n* wiadomości | administrator |
| **%serverlogs** | **serverlogs** *n* | wysyła w dm 10 logów serwera \| *n* logów | administrator |
| **%dc** *@user* | | usuwa użytkownika z kanału głosowego | administrator |


#### Konfiguracja serwera:  
| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :----- |:--- | :--- |
| **%zbudujserwer** | | automatycznie tworzy podstawowe kanały i rangi na serwerze | administrator |
| **%zbudujtext** *nazwa* | **%zbudujtext** *nazwa* *kategoria* | tworzy kanał tekstowy *nazwa* \| dodatkowo tworzy kategorię *kategoria* i go tam umieszcza | administrator |
| **%dodajtext** *nazwa* *kategoria* |  | tworzy kanał tekstowy *nazwa* i umieszcza go w kategori *kategoria*| administrator |
| **%zbudujvoice** *nazwa* | **%zbudujvoice** *nazwa* *kategoria* | tworzy kanał głosowy *nazwa* \| dodatkowo tworzy kategorię *kategoria* i go tam umieszcza | administrator |
| **%dodajvoice** *nazwa* *kategoria* |  | tworzy kanał głosowy i umieszcza go w kategori *kategoria* | administrator | 


#### Obliczenia:
| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :----- |:--- | :--- |
| **%decimalBIN** *liczba* | | zwraca zamienioną *liczbę* dziesiętna na binarną i pokazuje wizualizacje procesu liczenia| |
| **%hexaBIN** *liczba* | | zwraca zamienioną liczbę hexadecymalną na binarną | | 


#### Tworzenie kodów CRC:
| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :----- |:--- | :--- |
| **%allCRC** | | pokazuję listę dzielników CRC | |
| **%CRC** *ciąg_bitowy* *n_dodanych_bitów* *dzielnik* | | zwraca graficzne rozwiązanie wartości kodu CRC | |
| **randomCRC** *ilu_bitowy* *dzielnik* *wynik_w_bitach* | | zwraca graficzne rozwiązanie randomowego ciagu N-bitów pasującego do danego kodu CRC | |


#### Sprawdzanie sumy IP:
| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :----- |:--- | :--- |
| **%sumakontrolnaip** *ip_hexadecymal* | | zwraca sumę kontrolną w bitach i hexadecymalną oraz pokazuje proces liczenia | |
| **%weryfikacjasumykontrolnejip** *ip_hexadecymal* | | zwraca wynik sprawdzenia sumy kontrolnej ip oraz pokazuje proces liczenia | |
