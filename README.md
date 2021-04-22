![](ymir_gif/Ymir_banner.gif)
### Twórca: ***SCREAMIE#9946***  
[Zaproś Ymir na serwer](https://discord.com/oauth2/authorize?client_id=829256206170062888&permissions=8&scope=bot)
-------------------------------------------------------------------------------------

| Ymir_help | pokazuje aktualny prefix na serwerze |
| :--- | :--- |

![](ymir_gif/Ymir_help_command.gif)

## Spis komend:  
- [Komendy podstawowe](#komendy-podstawowe)
- [Moderacja](#moderacja)
- [Konfiguracja serwera](#konfiguracja-serwera)
- **Gry:**
  - [Wisielec](#gra-wisielec)
- [Przypomnienia](#przypomnienia)
- [Obliczenia](#obliczenia)
- [Tworzenie kodów CRC](#tworzenie-kodów-crc)
- [Sprawdzanie sumy IP](#sprawdzanie-sumy-ip)
- [System kontroli kanałów Ymir | *BETA TESTY*](#system-kontroli-kanałów-ymir-beta-testy)


### Komendy podstawowe:  

| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :--- |:--- | :--- |
| **%hi** | | wysyła informacje o bocie | |
| **%poke** *@user* | | wysyła wiadomość poke do wzkazanego użytkownika o ile nie jest botem, lub nie ma statusu "nie przeszkadzać" lub nie jest offline | |
| **%pokeALL** | | wysyła wiadomość do wszystkich użytkowników serwera o ile użytkownik nie jest offline i nie jest botem| administrator |
| **%forcepoke** *@user* | | wysyła wiadomość poke o ile dany użytkownik nie jest botem | administrator |
| **%say** *text* | | tworzy wpisany text w formie ramki, dodatkowo jeżeli jest to administrator to usuwa wiadomość z komendą | |
| **%sayRGB** *R* *G* *B* | | tworzy wpisany text w formie ramki o kolorze *RGB*, dodatkowo jeżeli jest to administrator to usuwa wiadomość z komendą | | 


### Moderacja:

| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :--- |:--- | :--- |
| **%zmienprefix** *prefix* | | ustawia prefix bota na *prefix* | administrator |
| **%clear** | **%clear** *n* | usuwa 1 wiadomość \| *n* wiadomości (max 200)| manage_messages |
| **%clearAV** *limit* *@user* | | usuwa tylko wiadomości wzkazanego *@user*, ***UWAGA*** *limit* to ilość wiadomości jakie bot ma ogólnie sprawdzić i usunąć w nich wiadomości autora *@user* a nie ile tych wiadomości tego autora ma usunąc (max 200 do sprawdzenia) | manage_messages |
| **%serverlogs** | **%serverlogs** *n* | wysyła w prywatnej wiadomości liczbę użytkowników oraz: 10 logów serwera \| *n* logów | administrator |
| **%dc** *@user* | | usuwa użytkownika z kanału głosowego | administrator |

### Przypomnienia:  

| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :--- |:--- | :--- |
| **%przypomnij** *dzień* *miesiąc* *rok* *treść* | | zapisuje przypomnienie na podaną datę i przy następnej zmianie z nieaktywnego na aktywny, w podanym dniu, bot wyśle wiadomość prywatną z *treść* (przypomnienie wyśle się tylko raz gdy nastąpi zmiana statusu) ***UWAGA 1*** jeżeli jesteś na dwóch serwerach gdzie jest Ymir, to bot wyśle podwójnie przypomnienie w tym samym czasie ***UWAGA 2*** możesz mieć tylko jedno przypomnienie! użycie drugi raz tej komendy, nadpisze aktualne przypomnienie| |
| **%usunprzypomnienie** | | usuwa przypomnienie | |   

*twórca bota nie ponosi odpowiedzialności za zamieszczane treści

### Konfiguracja serwera:  
| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :--- |:--- | :--- |
| **%zbudujserwer** | | automatycznie tworzy podstawowe kanały i rangi na serwerze | administrator |
| **%zbudujtext** *nazwa* | **%zbudujtext** *nazwa* *kategoria* | tworzy kanał tekstowy *nazwa* \| dodatkowo tworzy kategorię *kategoria* i go tam umieszcza | administrator |
| **%dodajtext** *nazwa* *kategoria* |  | tworzy kanał tekstowy *nazwa* i umieszcza go w kategori *kategoria*| administrator |
| **%zbudujvoice** *nazwa* | **%zbudujvoice** *nazwa* *kategoria* | tworzy kanał głosowy *nazwa* \| dodatkowo tworzy kategorię *kategoria* i go tam umieszcza | administrator |
| **%dodajvoice** *nazwa* *kategoria* |  | tworzy kanał głosowy i umieszcza go w kategori *kategoria* | administrator | 


### Gra wisielec:  
**Twórcy:** ***Magdalena#6689***, ***SCREAMIE#9946***  

![](ymir_gif/wisiel_command.gif)

| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :----- |:--- | :--- |
| **%egzekucja** | | rozpoczyna nową grę na danym kanale tekstowym - jedna gra może być grana na jednym kanale ale ilość grających osób na tym kanale jest nieograniczona| |
| **%zgaduje** *litera* | **%zgaduje** *słowo* | sprawdza czy dana *litera* pasuje \| czy dane *słowo* jest rozwiązaniem | | 

### Obliczenia:
**Twórcy:** ***Tomasz#0711***, ***SCREAMIE#9946***
| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :----- |:--- | :--- |
| **%decimalBIN** *liczba* | | zwraca zamienioną *liczbę* dziesiętna na binarną i pokazuje wizualizacje procesu liczenia| |
| **%hexaBIN** *liczba* | | zwraca zamienioną liczbę hexadecymalną na binarną | | 


### Tworzenie kodów CRC:

![](ymir_gif/CRC_command.gif)

| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :----- |:--- | :--- |
| **%allCRC** | | pokazuję listę dzielników CRC | |
| **%CRC** *ciąg_bitowy* *n_dodanych_bitów* *dzielnik* | | zwraca graficzne rozwiązanie wartości kodu CRC | |
| **%randomCRC** *ilu_bitowy* *dzielnik* *wynik_w_bitach* | | zwraca graficzne rozwiązanie randomowego ciagu N-bitów pasującego do danego kodu CRC | |


### Sprawdzanie sumy IP:

![](ymir_gif/IP_command.gif)

| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :----- |:--- | :--- |
| **%sumakontrolnaip** *ip_hexadecymal* | | zwraca sumę kontrolną w bitach i hexadecymalną oraz pokazuje proces liczenia | |
| **%weryfikacjasumykontrolnejip** *ip_hexadecymal* | | zwraca wynik sprawdzenia sumy kontrolnej ip oraz pokazuje proces liczenia | |


### System Kontroli Kanałów Ymir ***BETA TESTY***

***Jak to działa?***  
Po dodaniu danego kanału do bota, Ymir zacznie automatycznie reagować na dane zachowania na tym kanale.
Dla przykładu: administrator serwera ustawia kontrole na "zakaz przeklinania". Gdy ktos użyje wulgaryzmu,
Ymir automatycznie usunie taką wiadmość i wyśle komunikat o zakazie używania wulgaryzmów.  

***Czy jest bezpieczne?***  

Ymir przechowuje jedynie informacje o ID kanału oraz o przypisanej do niego permisji.
Także możesz spać spokojnie! Ymir nie będzie śledzić tego, co dziś jadłeś na śniadanko! :)  

**Przechowywane informacje:**  
-ID kanału serwera Discord  
-ID serwera Discord

**KOMENDY:**  

![](ymir_gif/skky_command.gif)

| Komenda | Dodatkowe opcje | Opis | Wymagana permisja |
| :--- | :----- |:--- | :--- |
| **%dodajkontrole** | | dodaje ten kanał do kontroli i domyślnie ustawia kontrolę na: zakaz przeklinania | administrator |
| **%usunkontrole** | | usuwa wszystkiego kontrole z tego kanału | administrator |
| **%infokontrola** | | wyświetla informacje o ustawieniach kontroli | administrator |
| **%kontrola** *permisja* | | ustawia kontrole na dane permisje | administrator |  


***Permisje***  
| Permisja | Opis | 
| :--- | :--- |
| **A** | zakaz używania wulgaryzmów |
| **L** | zakaz wysyłania linków | 

