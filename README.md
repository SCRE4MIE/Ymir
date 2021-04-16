# DOKUMENTACJA BOTA YMIR 

### Komendy Podstawowe: 
%hi | wysyła informacje o bocie
%poke @user | wysyła wiadomość poke do wzkazanego użytkownika
%say text | tworzy wpisany text w formie ramki
wymagana permisja: administrator
%zmienprefix prefix | ustawia prefix bota na wzkazany 
%clear (%clear n) | usuwa 1 wiadomość(n - wiadomości) 
%serverlogs (%serverlogs n) | wysyła w prywatnej wiadomości 10 logów serwera ( n- logów) 
%dc @user | po 10 sekundach wyrzuca wskazanego użytkownika 

Konfiguracja serwera:
wymagana permisja: administrator 
%zbudujserwer | automatycznie tworzy podstawowe kanały i rangi
%zbudujtext nazwa (%zbudujtext nazwa kategoria) | tworzy kanał tekstowy (tworzy kanał tekstowy i kategorie)
%dodajtext nazwa kategoria | tworzy i dodaje kanał tekstowy do istniejącej kategorii 
%zbudujvoice nazwa (%zbudujvoice nazwa kategoria) | tworzy kanał głosowy (tworzy kanal głosowy i kategorie)
%dodajvoice nazwa kategoria | tworzy i dodaje kanał głosowy do istniejącej kategorii

Obliczenia:
%decimalBIN liczba | zwraca zamienioną liczbę dziesiętna na binarną i pokazuje wizualizacje procesu liczenia
%hexaBIN liczba_w_hexa | zwraca zamienioną liczbę hexadecymalną na binarną

Tworzenie kodów CRC:
%allCRC | pokazuje listę dzielników CRC
%CRC ciag_bitowy n-dodanych_bitów dzielnik | zwraca graficzne rozwiązanie wartości kodu CRC
%randomCRC ilu_bitowy dzielnik wynik_w_bitach | zwraca graficzne rozwiązanie randomowego ciagu N-bitów pasującego do danego kodu CRC

Sprawdzanie sumy IP:
%sumakontrolnaip ip_hexadecymal | zwraca sumę kontrolną w bitach i hexadecymalną oraz pokazuje proces liczenia
%weryfikacjasumykontrolnejip ip_hexadecymal | zwraca wynik sprawdzenia sumy kontrolnej ip oraz pokazuje proces liczenia

System kontroli kanałów YMIR | BETA TESTY |

Jak to działa?

Po dodaniu ddanego kanału do bota, Ymir zacznie automatycznie reagować na dane zachowania na tym kanale.
Dla przykładu: administrator serwera ustawia kontrole na "zakaz przeklinania". Gdy ktos użyje wulgaryzmu,
Ymir automatycznie usunie taką wiadmość i wyśle komunikat o zakazie używania wulgaryzmów.

Czy jest bezpieczne?

Ymir przechowuje jedynie informacje o ID kanału oraz o przypisanym do niego permisji.
Także możesz spać spokojnie! Ymir nie będzie śledzić tego, co dziś jadłeś na śniadanko! :) 

Komendy:
wymagana permisja: administrator 
%dodajkontrole | dodaje ten kanał do kontroli i domyślnie ustawia kontrolę na: zakaz przeklinania
%usunkontrole | usuwa wszystkiego kontrole z tego kanału
%infokontrola | wyświetla informacje o ustawieniach kontroli 
%kontrola permisja | ustawia kontrole na dane permisje
    permisja:
        A = zakaz przeklinania
        L = zakaz wysyłania linków
    UWAGA! permisje możesz łączyć! np.: %kontrola AL <-- ustawi Ci kontrolę na zakaz przeklinania i wysyłania linków

